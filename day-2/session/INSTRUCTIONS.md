### 1. Check if Node is correctly installed
Run this command on your terminal
```
node -v
```
You should get something in the format of `v<version_no>` <br />
Ex: `v16.15.0`

### 2. Check if npm is correctly installed
Run this command on your terminal
```
npm -v
```

### 3. In your desired directory ( folder ), initialise a Vite project
```
npm create vite@latest
```

Give your project a name, select the `vanilla` framework and `vanilla` variant when prompted.

### 4. Enter your project directory
```
cd <your-project-name>
```

### 5. Run these two commands after changing the directory
```
npm install
```
```
npm run dev
```
Now go to  http://localhost:3000/ and see if a webpage loads.

### 6. Install three.js through npm
In your project directory, run this command
```
npm install --save three
```
