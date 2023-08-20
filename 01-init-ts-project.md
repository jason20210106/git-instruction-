# Steps to init a Typescript node project 


1. Create Project folder
```cmd
mkdir <your-project-name>
```

2. Move into the project folder

```cmd
cd <project name>
```

3. Init NPM
```cmd
npm init 
```

4. Install necessnary packages
```cmd
npm install -D ts-node typescript @types/node
```

5. Create Entry TS file <your-entry-file-name>


6. Inside package.json

```json
...
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "ts-node <your-entry-file-name>"
  },
...

```
7. To execute, you may
```cmd
npm start
```

or

```cmd
npx ts-node <your-entry-file-name>
```
