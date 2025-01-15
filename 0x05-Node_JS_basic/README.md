# 0x05. NodeJS Basics

![Node.js Basics](https://blogs.rakeshkamble.com/wp-content/uploads/2023/03/Nodejs-basics.jpg)

![Node.js Fundamentals](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/1/82692897e15d9f03256f.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20250115%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250115T172350Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=afa54b136ad39cfd66f6e7b6ec7e605c5be1dae8416674f853b107c9e3fe80ae)

This project introduces the fundamentals of **Node.js** and **Express.js** for backend development. You'll learn how to build and manage a simple HTTP server, use various Node.js modules, handle asynchronous operations, and create advanced routes with Express.

---

## Learning Objectives

By the end of this project, you should be able to:

- Run JavaScript using Node.js.
- Utilize Node.js modules to enhance functionality.
- Read files using specific Node.js modules.
- Access command-line arguments and environment variables using `process`.
- Create a basic HTTP server using Node.js.
- Build a small HTTP server using Express.js.
- Implement advanced routing with Express.js.
- Use ES6 features in Node.js with Babel.
- Speed up development using **Nodemon**.
- Write and run tests using **Jest**.
- Ensure code quality using **ESLint**.

---

## Resources

To complete this project, it is recommended to read or watch the following:

- [Node.js Getting Started](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [Process API Documentation](https://nodejs.org/dist/latest-v12.x/docs/api/process.html)
- [Child Process Documentation](https://nodejs.org/dist/latest-v12.x/docs/api/child_process.html)
- [Express Getting Started](https://expressjs.com/en/starter/installing.html)
- [Mocha Documentation](https://mochajs.org/)
- [Nodemon Documentation](https://nodemon.io/)

---

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`, **Visual Studio Code**.
- All files will be interpreted or compiled on **Ubuntu 18.04 LTS** using Node.js version **12.x.x**.
- All files must end with a new line.
- Your code should have a `.js` extension.
- A `README.md` file at the root of the project folder is mandatory.
- Code will be tested using **Jest** and the command `npm run test`.
- Code must pass lint verification using **ESLint**.
- To ensure the entire project meets the requirements, run `npm run full-test`.
- Functions or classes must be exported using the format:  
  ```javascript
  module.exports = myFunction;
