### TL;DR 

```ts
 import * as M from 'pattern-matching-ts/match'
 
 const match = (about: About) =>
    pipe(
      about,
      M.matchW('_tag')({
         Role: () => 'Software Engineer @ `https://beefree.io/',
         Focus : () => ({ TypeScript , React , Node }),
         Currently: () =>'Hacking in TypeScript & Rust',
         AllAbout: () =>  ['Open Source','Functional Programming','Clean code'],
      })
    )

```


[LinkedIn](https://www.linkedin.com/in/stefanoregosa/) | [Twitter](https://twitter.com/thenrdlab) | [Dev.to](https://dev.to/stefano_regosa)

