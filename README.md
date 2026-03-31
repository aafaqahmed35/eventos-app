🎉 Eventos

Imagine planning an event without the chaos.

No endless calls.
No scattered information.
No confusion.

This platform brings everything into one place.

⸻

What is this?

A full-stack Event Management System built using Next.js that allows users to discover, organize, and manage events seamlessly.

From venues to photographers, catering to logistics — everything is integrated into a single platform.

⸻

The Idea:

Event planning is often fragmented across multiple platforms.

This project solves that by:

•	Centralizing event services
	•	Providing personalized recommendations
	•	Offering a structured dashboard for users

⸻

How it Works:
	•	Users sign up and onboard into the system
	•	Explore different event services
	•	Get recommendations based on preferences
	•	Manage activities via a dashboard
	•	Backend APIs handle logic, authentication, and data

⸻

Project Structure:

eventos/
│
├── app/                  → Main application (Next.js App Router)
│   ├── api/              → Backend API routes
│   ├── dashboard/        → User dashboard
│   ├── login/            → Authentication pages
│   ├── profile/          → User profile pages
│   └── page.tsx          → Home page
│
├── components/           → Reusable UI components
│   ├── Navbar.tsx
│   ├── Sidebar.tsx
│   ├── Cards, Buttons, etc.
│
├── models/               → MongoDB schemas (User, Vendor, etc.)
├── lib/                  → Database connection (MongoDB config)
├── public/               → Static assets (images, icons)
├── utils/                → Helper functions
│
├── package.json          → Dependencies and scripts
├── next.config.ts        → Next.js configuration
└── tailwind.config.ts    → Tailwind CSS configuration


⸻

Tech Stack:
	•	Next.js (App Router)
	•	React
	•	Tailwind CSS
	•	MongoDB
	•	NextAuth

⸻

💻 Running the Project:

Clone the repository:

git clone https://github.com/aafaqahmed35/eventos-app.git
cd eventos

Install dependencies:

npm install

Run the server:

npm run dev

Open:

http://localhost:3000


⸻

🔐 Environment Variables (Optional)

Create a .env.local file:

MONGODB_URI=your_connection_string
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000


⸻
Future Improvements
	•	Search & filtering
	•	Save/bookmark events
	•	Calendar integration
	•	Payment gateway
	•	AI recommendations

⸻

Author:

Aafaq Ahmed

⸻
Note

This project is inspired by an open-source implementation and has been modified and enhanced for learning purposes.
