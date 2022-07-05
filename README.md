# The First
- You need install NodeJS
    - You can visit 'https://nodejs.org/en/' to download and install.
- Setup Git and clone project.
- Install TypeScript
```
npm install typescript --save-dev
```
We recommend creating a tsconfig.json inside your cypress folder with the following configuration:
```
{
  "compilerOptions": {
    "target": "es5",
    "lib": ["es5", "dom"],
    "types": ["cypress", "node"]
  },
  "include": ["**/*.ts"]
}
```
# Extensions for VSCode
 - Cypress Helper - Author: Oleksandr Shevtsov
 - Cypress Snippets - Author: Andrew Smith
 - Chai snippets - Author: Nick Hatt

### Note: All command will run on the project root folder

## How to open Cypress UI
 - Run this command
```
npm run open
```
## How to run test script
 - Run all test script
 ```
 npm run all-test
 ```
 - Run one test script
```
npm run one-test -- <path test script>
```
