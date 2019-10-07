# angular-package-library
Hi there, this this small snippets to learn about Angular package the library :)

1) first create blank angualr project `new new demo`
2) hit this command to create lib - `ng generate library my-lib`

3) then it will create library inside project directory -> inside library delete all files expect `my-lib.module.ts` file, then create following files - 

```js 
my-lib.component.ts
my-lib.component.scss
my-lib.component.html
my-lib.component.spec.ts
//my-lib.module.ts
```

4) work on functionality that whatever you want do with above files after that you have to build your project - so hit followsing commands -
```js
ng build my-lib
```
it will create following directory -
```js

dist/<library-name>

```

5) Publishing your library to NPM

```js
ng build my-lib
cd dist/my-lib
npm publish
```

6) You can build, test, and lint the project with CLI commands:

  ```js
ng build my-lib
ng test my-lib
ng lint my-lib
  ```

7) Reference links - https://youtu.be/l3wjN4datGs
