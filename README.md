### Step-by-Step Instructions to Install Node.js

#### 1. **Installing Node.js on Major Operating Systems**

**For Windows:**
1. Download the Node.js installer from the official website: [https://nodejs.org](https://nodejs.org).
2. Run the installer and follow the setup instructions.
3. After installation, open **Command Prompt** and type:
   ```
   node -v
   ```
   This command should display the installed version of Node.js, confirming the installation.

**For macOS:**
1. The easiest way to install Node.js on macOS is via **Homebrew**. First, install Homebrew by running:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. After Homebrew is installed, run the following to install Node.js:
   ```
   brew install node
   ```
3. Verify the installation by running:
   ```
   node -v
   ```

**For Linux (Ubuntu/Debian-based):**
1. You can install Node.js using the package manager `apt`. First, update your package list:
   ```
   sudo apt update
   ```
2. Install Node.js using the following command:
   ```
   sudo apt install nodejs
   ```
3. Optionally, install npm (Node Package Manager) to manage packages:
   ```
   sudo apt install npm
   ```
4. Verify the installation by running:
   ```
   node -v
   ```

#### 2. **Create a "Hello World" Program in Node.js**

Once Node.js is installed, create a simple "Hello World" program.

### Node.js Script: `hello-world.js`

Create a file named `hello-world.js` and add the following code:

```javascript
// hello-world.js

// This simple program outputs "Hello, World!" to the console
console.log('Hello, World!');
```

#### 3. **Running the Script**

To run the program:
1. Open a terminal or command prompt.
2. Navigate to the directory where `hello-world.js` is saved.
3. Run the script using Node.js:
   ```
   node hello-world.js
   ```

You should see the output:

```
Hello, World!
```

### Full Code for `hello-world.js`:

```javascript
// hello-world.js

// This simple program outputs "Hello, World!" to the console
console.log('Hello, World!');
```
