<!-- //Slightly more complex endpoint test -->
//zod also 
//also we will see how header will test when we will request to get request by supertest
1. npm init --y
2. npx tsc --init
3. "rootDir": "./src",
4. "outDir": "./dist",
5. npm install --save-dev ts-jest  @jest/globals @types/express
6. npm i supertest @types/supertest
7. npm install express 
8. npx ts-jest config:init
9. create src/index.ts
10.  Update package.json scripts
        "test": "jest"
11.   see in index.ts and bin.ts
12. tsc -b
13. node dist/bin.js to start the port    
14. npm i zod