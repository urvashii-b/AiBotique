# ArBotique - AR & AI Fashion Store

Welcome to the ArBotique project, a part of the Kodikon Hackathon. ArBotique is an AR and AI Fashion Store with a focus on AI-powered 3D shirt generation.

## Steps to Use:

1. *Set Up Environment Variables*
   - Create a .env file in both the client and server directories.
   - In the client .env file, add the following line:
   VITE_URL = http://localhost:8080/api/v1/dalle

  In the sever .env file, add the following line:
  OPENAI_API_KEY = <YOUR_API_KEY>
  
2. *Install Dependencies*
  - Navigate to both the client and server directories in your terminal.
  - Run the following command to install the project dependencies for both the client and server:
  npm i in both client and server folders

3. *Start the Server*
 - In the server directory, start the server by running:
 npm start in the server

4. *Run the Client*
  - In the client directory, run the following command to start the client in development mode:
 npm run dev in the client

5. *AR Implementation*
- ArBotique is implementing stable diffusion with human body tracking to capture the user and fit clothes accordingly. Please refer to the specific documentation or code related to this AR feature for more details.

Now you're all set to explore the ArBotique project! Enjoy your AR and AI fashion store experience.

Happy coding!
