Teaching fundamental functional programming features of Javascript.

Many functional programming learning resources will teach you to write functional code, but it's often highly indirect, deeply abstracted, requires understanding complex relationships between custom library calls, and doesn't represent the reality of how people actually write JavaScript.

The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idiomatic JavaScript.

Please read the exercises thoroughly and obey all conditions, they are there to help you learn!
Installation & Update

$ npm install -g functional-javascript-workshop@latest

Some npm installations require use of sudo in the above command. Recommend to instead reinstall node/npm so you don't need sudo.
Usage Instructions
1. Selecting a problem to work on

Once the workshop is installed, run functional-javascript-workshop to print a menu where you can select a problem to work on.

$ functional-javascript-workshop

Problems are listed in rough order of difficulty. You are advised to complete them in order, as later problems will build on skills developed by solving previous problems.
2. Writing your solution

Once you have selected a problem, the workshop will remember which problem you are working on. Using your preferred editor, simply create a file to write your solution in. Most problems will supply some boilerplate with which to get started. Copy this from the problem description to your solution file.
3. Testing your solution

Use the workshop's run command to point the workshop at your solution file. Your solution will loaded and passed the problem input. This usually won't perform any validation, it will only show the program output.

$ functional-javascript-workshop run mysolution.js

4. Verifying your solution

Your solution will be verified against the output of the 'official' solution. If all of the output matches, then you have successfully solved the problem!

$ functional-javascript-workshop verify mysolution.js