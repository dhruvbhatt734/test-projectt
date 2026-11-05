# test-projectt

// const http = require("http");

// const server = http.createServer((req, res) => {
// res.writeHead(200, {
// "Content-Type": "text/plain"
// });

// ```
// res.end("hello node.js");
// ```

// });

// server.listen(3000, () => {
// console.log("Server running on port 3000");
// });

// try{
//     console.log("program started");

//     let result = 10/10;
//     console.log(result);

//     throw new Error ("something went wrong");

// }
// catch(error)
// {
//     console.log("error" , error.message)
// }

// finally{
//     consloe.log("Program End ")
// }

// 

function greet(name) {
    console.log("hello " + name);
}

function user(callback) {
    console.log("Welcome to JavaScript");

    callback("Daroga ji ");
}

user(greet);
