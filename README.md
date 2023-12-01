### Running the Project using Docker:

1. **Clone the Repository**:
   - Copy this link: [Book Club Repository](https://github.com/mjadoum/book-club)
   - Create a new environment and paste the link into your new development environment.

2. **Setup and Configuration**:
   - Click on the create button to initialize the setup process.
   - Once finished, open `server6` in Visual Studio Code (VSC) and navigate to the terminal.

3. **Setting Password**:
   - Set the password to 'node' using the command:
     ```
     passwd
     ```

4. **Installing Dependencies**:
   - Change directory to `myapp` using:
     ```
     cd myapp
     ```
   - Switch user to 'node':
     ```
     su node
     ```
   - Install project dependencies:
     ```
     npm install
     ```

5. **Updating NPM**:
   - Go back to the root user:
     ```
     su root
     ```
   - Update npm globally to version 10.2.4:
     ```
     npm install -g npm@10.2.4
     ```
   - Switch back to 'node':
     ```
     su node
     ```

6. **Running the Application**:
   - Start the application:
     ```
     npm run start
     ```

7. **Accessing the Application**:
   - Open your browser and navigate to:
     [http://127.0.0.1:3000/catalog](http://127.0.0.1:3000/catalog)

