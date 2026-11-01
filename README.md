#instructions and Notes

## In this session 1...

**Writing the First Test**

1.Target web App : 'https://katalon-demo-cura.herokuapp.com/'

2.Step
    1. Go to the home page
    2. assert if the title is correct
    3. Assert header text
3.done

**Common Errors**
1. spec/test file not having '.spec or .test' init
2. Navigation timeout error

use : {
      navigationTimeout: 30_000, //set timeout to 30 second
},


3. Missing 'await' keyword before action
4. Done

**run scripts fast**

1. Add shortcut to 
 
  "scripts": {
    "demo" : "npx playwright test tests/demo/mytest.spec.ts --headed",
    "test": "npx playwright test"
  }

2. To execute  : npm run demo
3. Done!

## In this Session 2 - INSTALL codegen extension

**Options 1 - Install vs code extentions
1. VS code Extension -> 'Playwright Test for VSCode'

**Options 2 - CLI

