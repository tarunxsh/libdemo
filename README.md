setup package
    mkdir libdemo
    cd libdemo
    npm init
    npm i typescript
    npx tsc --init
    configure tsc out dir in tsconfig
    setup lib entry file: "main": "lib/index.js" in package.json
    setup files to be published: "files": ["lib/**/*"] in package.json

create basic src/index.ts

publish pkg: 
    npm run build
    npm login
    npm publish --access=public