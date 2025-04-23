# Search
## Linear search & kata setup

- yarn install
- yarn generate
- `src/day1/LinearSearchList.ts`

```ts
export default function linear_search(haystack: number[], needle: number): boolean {
    for(let i = 0; i< haystack.length; i++){
        if(haystack[i] === needle){
            return true;
        }
    }
    return false;
}
```

- test alg. 

```sh
npx jest Linear
```

## BinarySearchList
- cd kata-machine/src/day1

- TEST
```sh
npx jest Binary
```

```ts
export default function bs_list(haystack: number[], needle: number): boolean {
    
    let lo = 0;
    let hi = haystack.length;

    do{
        const m = Math.floor(lo + (hi-lo)/2 );
        const v = haystack[m];
    
        if(v === needle){
            return true;
        } else if (v > needle){
            hi = m;
        } else{
            lo = m + 1;
        }
    
    } while (lo < hi);

    return false;
}

```

- easier to understand
```ts
export function bs_list(haystack: number[], needle: number): boolean {
    let lo = 0, hi = haystack.length - 1;

    while (lo <= hi) {
        const m = Math.floor((lo + hi) / 2);

        if (haystack[m] === needle) {
            return true;
        } else if (haystack[m] < needle) {
            lo = m + 1;
        } else {
            hi = m - 1;
        }
    }

    return false;
}
```