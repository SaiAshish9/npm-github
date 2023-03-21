https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

https://docs.github.com/en/packages/learn-github-packages/configuring-a-packages-access-control-and-visibility

https://docs.gitlab.com/ee/user/packages/package_registry/

https://docs.gitlab.com/ee/user/packages/npm_registry/

https://docs.gitlab.com/ee/user/packages/workflows/working_with_monorepos.html

https://github.com/joelparkerhenderson/monorepo-vs-polyrepo

https://www.youtube.com/watch?v=m2cPEwwf8bc

https://2ality.com/2021/07/simple-monorepos.html#:~:text=Simple%20monorepos%20via%20npm%20workspaces%20and%20TypeScript%20project%20references,-%5B2021%2D07%2D&text=A%20monorepo%20is%20a%20single,built%20into%20npm%20and%20TypeScript.

<img width="1784" alt="Screenshot 2023-03-21 at 9 26 54 PM" src="https://user-images.githubusercontent.com/43849911/226666501-daa8d973-868b-400e-b3b6-b01bf6386103.png">

<img width="1792" alt="Screenshot 2023-03-21 at 9 40 46 PM" src="https://user-images.githubusercontent.com/43849911/226670369-c1ac7d0a-9941-41ec-aa0b-026c406f2e18.png">

<img width="1785" alt="Screenshot 2023-03-21 at 10 20 09 PM" src="https://user-images.githubusercontent.com/43849911/226682717-fd48c9c4-bca2-4259-9e7b-f217158d716c.png">

<img width="1792" alt="Screenshot 2023-03-21 at 10 35 44 PM" src="https://user-images.githubusercontent.com/43849911/226686933-cc71c2bf-48d4-4725-bbae-8b4e45b3a10c.png">

<img width="715" alt="Screenshot 2023-03-21 at 10 39 47 PM" src="https://user-images.githubusercontent.com/43849911/226687882-c250dffd-0d0b-4307-ac9a-52693151b03b.png">

<img width="599" alt="Screenshot 2023-03-22 at 12 34 43 AM" src="https://user-images.githubusercontent.com/43849911/226714659-97696809-4330-4dfe-9853-b1fdc0ed381b.png">

https://egghead.io/courses/introduction-to-monorepos-with-npm-workspaces-c03f500b

```
npm publish --access public
 
will not connect to repo.
```

```
npm login --scope=@NAMESPACE --auth-type=legacy --registry=https://npm.pkg.github.com

username 
access_token

npm publish
npm notice 
npm notice 📦  @saiashish9/npm-test-sai@1.0.1
npm notice === Tarball Contents === 
npm notice 20B  index.js    
npm notice 446B package.json
npm notice === Tarball Details === 
npm notice name:          @saiashish9/npm-test-sai                
npm notice version:       1.0.1                                   
npm notice filename:      @saiashish9/npm-test-sai-1.0.1.tgz      
npm notice package size:  395 B                                   
npm notice unpacked size: 466 B                                   
npm notice shasum:        9e4b00e3e52fde3828401f6747f915e8ebf212bc
npm notice integrity:     sha512-9zshjcSp3FBaL[...]+KA68W4F2xAdg==
npm notice total files:   2                                       
npm notice 
npm notice Publishing to https://registry.npmjs.org/
+ @saiashish9/npm-test-sai@1.0.1
```

```
npm publish --registry=https://npm.pkg.github.com/
```

<img width="1792" alt="Screenshot 2023-03-21 at 10 13 04 PM" src="https://user-images.githubusercontent.com/43849911/226680866-df94d1ae-b2fe-4a7c-b6de-7b2933e2795b.png">
