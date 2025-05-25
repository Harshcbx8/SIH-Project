🧠 GAIL Multilingual AI Chatbot - Smart India Hackathon 2024
A multilingual AI-powered chatbot developed for Smart India Hackathon 2024, addressing GAIL's problem statement to automate customer and employee support using intelligent, real-time, and multilingual solutions.

🚀 Project Overview
This project was created in response to a challenge presented by GAIL (India) Limited under the Smart India Hackathon 2024. The objective was to build an interactive and intelligent AI chatbot system capable of handling multilingual conversations, supporting document uploads, and assisting both customers and employees with their queries in real-time.

The solution focused on combining Natural Language Processing (NLP), cloud services, real-time communication, and security protocols into a seamless web and mobile interface.

⚠️ The frontend was completed using React and related tools, but the backend was only conceptually designed, as the project was not selected for the final implementation phase.

🖼️ UI Snapshots
Here are screenshots showcasing the UI of the chatbot:

signin	home
newsletter	ai
💡 Core Features
🔤 Multilingual AI Chat: Seamless conversation in multiple languages using NLP engines like Dialogflow or Hugging Face Transformers.
⚡ Real-Time Messaging: Multi-user communication enabled by Socket.io.
🧠 AI-Powered Query Resolution: Intelligent response system based on deep learning models.
🔐 Secure Authentication: Planned 2FA using Firebase Authentication or email-based verification.
🧹 Language Moderation: Dictionary-based bad language filtering stored in MongoDB.
📁 Document Upload & Analysis: Planned integration with AWS S3 or Google Cloud Storage for managing document queries.
🖥️ Mobile-Responsive UI: Built using Tailwind CSS to ensure cross-device compatibility.
🛠️ Tech Stack
Frontend
React.js – Building dynamic UI components
Vite – Fast bundler and dev environment
Tailwind CSS – Utility-first CSS framework for responsive design
Socket.io (Client) – For real-time messaging
Proposed Backend (Not Implemented)
Node.js & Express.js – RESTful API development
MongoDB – For storing user profiles, messages, and NLP results
Firebase Authentication / NodeMailer – For 2FA implementation
Socket.io (Server) – Multi-user real-time backend
AWS S3 / Google Cloud – For document storage and NLP-based analysis
Dialogflow / Transformers (NLP) – For intelligent conversation handling
TensorFlow.js / PyTorch – For potential deep learning tasks
📁 Folder Structure (Frontend Only)
SIH_Client/
├── public/                # Static assets
├── src/
│   ├── components/        # Chat UI, Header, Footer, etc.
│   ├── pages/             # Main pages like Chat, Home
│   ├── utils/             # Constants and helper functions
│   └── App.jsx            # Root component
├── tailwind.config.js     # Tailwind configuration
├── vite.config.js         # Vite bundler setup
├── package.json           # Project dependencies and scripts
🧪 Getting Started
To run the frontend locally:

# Clone the repository
git clone https://github.com/HemantBatra873/SIH-Project
cd SIH_Client

# Install dependencies
npm install

# Start the development server
npm run dev
🌐 Key Use Cases
GAIL customers querying about billing, services, and gas-related FAQs.
GAIL employees checking HR, compliance, and internal document resources.
Document-based Q&A for uploaded forms or complaints.
Handling queries in multiple Indian and international languages.
🔮 Future Enhancements
Backend integration with MongoDB and Express.js for full functionality
Use of LLMs like Gemini, Mistral for advanced comprehension
Mobile app with React Native
Admin panel for chat monitoring and analytics
Multimodal support (voice + text)
📢 Acknowledgements
GAIL (India) Ltd. – Problem Statement Provider
Smart India Hackathon Organizers – For the opportunity
Our Team – For frontend development and architecture planning
📄 License
This project is built for academic and hackathon demonstration purposes. All intellectual rights are retained by the developers and contributors.
