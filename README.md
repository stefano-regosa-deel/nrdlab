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


- 🎧 ***Full Remote*** since 2013
- 💼  I'm currently working as a **Software Engineer** in the **[Bee](https://beefree.io/)** unit of **[Mailup](https://www.mailup.it/)**
- 🗣  I'm all about **clean code**, **functional programming** and **Open source**.
- ⚙️   I love to code in **TypeScript**, **React**, **Node.js**
- 🔭  I'd like to work more on **Rust**

[LinkedIn](https://www.linkedin.com/in/stefanoregosa/) | [Twitter](https://twitter.com/thenrdlab) | [Dev.to](https://dev.to/stefano_regosa)

