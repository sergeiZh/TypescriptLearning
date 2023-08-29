# TypescriptLearning
Learning project to start write on TypeScript

# Environment installation

1. Initialize project\
`npm init`
2. Install TypeScript globally\
`npm install -g typescript`
3. Install server to run project locally with on-fly changes\
`npm install --save-dev lite-server`
4. To run TypeScript files\
`tsc <file name>.ts`\
or if it fails to run use\
`npx tsc <file name>.ts`
5. Run whole project\
In **package.json** file, in **scripts** section add new script with starting installed lite-server\
`"start": "lite-server"`\
after that just run the command in directory, where **index.html** file resides\
`npm start`
