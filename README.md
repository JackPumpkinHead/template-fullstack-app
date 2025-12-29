<div id="header" align="center">
  <h1>Tempalte for new fullstack applications</h1>
  <h3>Tool for creating new app.</h3>
  <h3>🛠 Stack:  </h3>
  <h3>
   <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  </h3>
</div>

## Description
To speed up the development of a new project, the template contains ready-made settings for:
1. working with the workspace monorepository
2. trpc type checking,
3. linter and prettier
4. Husky for checking and formatting commits.


All checks are performed automatically when creating a commit.

## Quick Start
The monorepo consists of two folders web\back.  
If you only need the front\back, you can keep only the web\back folder you need.  

Install packages  
```
pnpm i
```  

Setup husky scripts:  
```
pnpm prepare
```  
