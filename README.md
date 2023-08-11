### TL;DR 

```ts
 import * as M from 'pattern-matching-ts/match'
 
 const match = (about: About) =>
    pipe(
      about,
      M.matchW('_tag')({
         Name: () => 'Stefano Regosa',
         Role: () => 'Software Engineer, Technical Leader, and Frontend Architect',
         Focus : () => ({ TypeScript , React , Node }),
         Currently: () => 'Hacking in TypeScript & Rust',
         Blog: () => 'https://undefined.technology/',
         AllAbout: () =>  ['Open Source','Functional Programming',' FrontEnd Architectures'],
        
      })
    )

```


[Blog](https://undefined.technology/) | [Website](https://stefanoregosa.com) | [LinkedIn](https://www.linkedin.com/in/stefanoregosa/) | [Twitter](https://twitter.com/thenrdlab) | [Dev.to](https://dev.to/stefano_regosa)

