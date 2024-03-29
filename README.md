**README: Promptopia - Discover & Share AI-Powered Prompts**

**Introduction:**
This project, Promptopia, was developed as a part of learning Next.js through the JavaScript Mastery channel. It serves as a platform for discovering and sharing AI-powered prompts. This README aims to provide an overview of the project, its features, and how to set it up locally.

**Features:**
- **Discover Prompts:** Users can explore a variety of prompts generated by AI.
- **Share Prompts:** Users can share their own prompts with the community.
- **AI-Powered:** The prompts are generated using artificial intelligence, making them diverse and engaging.
- **User Authentication:** Users can sign up, log in, and maintain their profiles.
- **Search Functionality:** Users can search for prompts based on keywords or categories.
- **Responsive Design:** The application is designed to be responsive, ensuring a seamless experience across different devices.

**Technologies Used:**
- **Next.js:** A React framework for building server-side rendered and static web applications.
- **React:** A JavaScript library for building user interfaces.
- **Node.js:** A JavaScript runtime for building server-side applications.
- **MongoDB:** A NoSQL database used for storing user data and prompts.
- **Tailwind CSS:** A utility-first CSS framework for styling the application.
- **Firebase:** Used for user authentication.

**Setup Instructions:**
1. Clone the repository: `git clone https://github.com/yourusername/promptopia.git`
2. Navigate to the project directory: `cd promptopia`
3. Install dependencies: `npm install`
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Define the following variables:
     - `MONGODB_URI`: URI for connecting to MongoDB.
     - `JWT_SECRET`: Secret key for JWT authentication.
     - `OPENAI_API_KEY`: API key for accessing OpenAI  authentication.
     - `FIREBASE_AUTH_DOMAIN`: Firebase authentication domain.
     - `FIREBASE_PROJECT_ID`: Firebase project ID.
     - `FIREBASE_STORAGE_BUCKET`: Firebase storage bucket.
     - `FIREBASE_MESSAGING_SENDER_ID`: Firebase messaging sender ID.
     - `FIREBASE_APP_ID`: Firebase app ID.
5. Start the development server: `npm run dev`
6. Access the application in your browser at `http://localhost:3000`

**Acknowledgment:**
Special thanks to JavaScript Mastery channel for providing valuable tutorials and resources on learning Next.js. This project wouldn't have been possible without their guidance and support.

**Note:**
This is my first project built using Next.js. Your feedback and contributions are highly appreciated.

**Author:**
Najas Nazar

**License:**
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).