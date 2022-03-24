### TL;DR 

```ts
 import * as M from 'pattern-matching-ts/match'
 
 const match = (about: About) =>
    pipe(
      about,
      M.matchW('_tag')({
         Name: () => 'Stefano Regosa',
         Role: () => 'Senior Software Engineer @ TreatWell',
         Focus : () => ({ TypeScript , React , Node }),
         Currently: () =>'Hacking in TypeScript & Rust',
         AllAbout: () =>  ['Open Source','Functional Programming','FrontEnd Architectures']
      })
    )

```


[LinkedIn](https://www.linkedin.com/in/stefanoregosa/) | [Twitter](https://twitter.com/thenrdlab) | [Dev.to](https://dev.to/stefano_regosa)

