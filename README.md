Hawkeye: AI-Powered Video Anomaly Detection
Hawkeye is a multimodal surveillance system developed as a group project to automate the detection of irregular activities in video feeds. By leveraging Gemini 3 Flash, the system moves beyond simple motion detection to provide intelligent, natural language analysis of incidents like road accidents and security breaches.

🚀 Key Features
Multimodal Video Analysis: Utilizes the Gemini 3 Flash API to process video frames and understand complex scenes.

Structured Incident Reporting: Generates automated reports in JSON format, capturing event descriptions, timestamps, and severity levels.

User-Friendly Dashboard: A responsive web interface built with React and TypeScript for seamless video uploads and result visualization.

Real-time Potential: Designed with an architecture capable of scaling to live webcam or CCTV stream analysis.

🛠️ Tech Stack
Frontend: React.js, TypeScript, Tailwind CSS.

AI Engine: Google Gemini 3 Flash (via Google AI Studio).

Version Control: Git & GitHub for team collaboration.

📂 Project Structure
Plaintext
├── src/
│   ├── components/       # UI for video uploads and result display
│   ├── services/         # Gemini 3 Flash API integration logic
│   ├── hooks/            # Logic for frame extraction and processing
│   └── types/            # TypeScript interfaces for structured AI responses
├── public/               # Static assets
└── .env.example          # Environment variable template for team members
⚙️ Setup for Contributors
Clone the Repo: git clone https://github.com/Steve087/hawkeye.git

Install Deps: npm install

API Key: Create a .env file based on .env.example and add your VITE_GEMINI_API_KEY.

Launch: npm run dev

👥 Contributors
Rohith Mungath
Steve Jose
Christo Pius
Aleetta Mariya Sebastian





[Team Member Name] – [Role, e.g., Backend Services & API Management]

Academic Context: This project was developed by students from CEC (KTU).
