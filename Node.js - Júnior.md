Pergunta 1/16:
When a javaScript function is invoked (called) in Node, where is a new frame placed?
- [x] the call stack
- [ ] the events queue
- [ ] the event loop
- [ ] the poll phase


Pergunta 2/16:
Which fs module method can be used to read thecontent of a fle without buffering it in memory?
- [x] `createReadStream`
- [ ] `readFileSync`
- [ ] `readFile`
- [ ] `read`

Pergunta 3/16:
How do you check that a value is a date object in Node?
- [ ] `util.date(value)`
- [ ] `console.isDate(value)`
- [ ] `assert.isDate(value- [ ])`
- [x] `util.types.isDate(value)`

Pergunta 4/16:
What is the purpose of the file system (fs) module?
- [ ] to provide methods to work with databases
- [ ] to provide methods to work with requests and responses
- [x] to provide methods to work with files
- [ ] to find new file systems

Pergunta 5/16:
How can you count the number of logical CPUs on the machine that is running Node?
- [x] `node -p "os.cpus().length"`
- [ ] `node -p "util.cpus().size"`
- [ ] `node -p "process.cpus"`
- [ ] `node -p "process.os.cpus"`

Pergunta 6/16:
Which object is used to manage the cache of required modules?
- [ ] `process.cache`
- [ ] `module.cache`
- [ ] `global.cache`
- [x] `require.cache`

Pergunta 7/16:
How can you use the promise API with a callback-based function like child_process.exec?
- [ ] `util.promisify(child_process.exec)`
- [ ] `new Promise(child_process.exec)`
- [x] `util.promisify(child_process.exec())`
- [ ] `new Promise(child_process.exec())`

Pergunta 8/16:
What can you export with module.exports?
- [ ] only objects.
- [ ] only variables and arrays
- [x] functions, objects, arrays, or anything you assign to the module
- [ ] only functions

Pergunta 9/16:
Which of the following is NOT a valid stream in Node?
- [ ] `process. stdin`
- [ ] `process. stderr`
- [ ] `process. stdout`
- [x] `process. stdinfo`

Pergunta 10/16:
What is the Node LTS version?
- [x] It is the safest version for long-term support.
- [ ] It is the current unstable version and is to be avoided.
- [ ] It is the version with the latest features.
- [ ] It is the version that will be retired soon.

Pergunta 11/16:
Which statement is true when you run the code shown below?
require('child_process').fork('script.js');
- [ ] The forked process shares the event loop with the parent process
- [ ] A new VM instance is created and the two VM instances will be shared between the forked process and the parent process.
- [x] The forked process will have its own VM instance.
- [ ] The forked process shares the same VM thread with the parent process.

Pergunta 12/16:
Looking at the code below, what does the console show?
```js
const http = require('http');
const hostname = '127.0.0.1'; const port = 3000;
const server = http.createServer((req, res) => {
res.statusCode = 200; res.setHeader("Content-Type", "text/plain"); res.end("Hello World\n");
});
server.listen(port, hostname, () => { console.log(`server running at http://${hostname}:${port}/`); });
```
- [ ] `server running at http://localhost:3000/`
- [ ] `server running at http://localhost:4000/`
- [x] `server running at http://127.0.0.1:3000/`
- [ ] `server running at port 3000`

Pergunta 13/16:
What is the purpose of the path module?
- [ ] It is a retiring module.
- [ ] to provide utilities to add and remove files
- [ ] to provide utilities to test files
- [x] to provide utilities to play with file and directory paths

Pergunta 14/16:
What does the code shown below do?
```js
const fs = require('fs'); const os = require('os');
const system = os.platform(); const user = os.userInfo().username;
fs.appendFile('hello.txt', `Hello ${user} on ${system}`, (err) => { if (err) throw err; console.log('The data was appended to file!');}
);
```
- [ ] creates a file named data and append numbers
- [ ] console logs system information
- [x] creates a text file hello.txt and appends customized text
- [ ] creates an image file

Pergunta 15/16:
You have a script.js file with the single line of code shown here. What will be the output of executing script.js with the node command?
```js
console.log(arguments);
```
- [ ] ReferenceError: arguments is not defined
- [ ] undefined
- [x] an object representing an array that has five elements
- [ ] an empty string

Pergunta 16/16:
What are the arguments passed to the module wrapper function?
- [ ] `exports, process, require, module, __filename, __dirname`
- [ ] `exports, module, __filename, __dirname`
- [x] `exports, require, module, __filename, __dirname`
- [ ] `exports, __filename, __dirname`
