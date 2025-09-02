# HealthTrack: Your Pocket Health Companion 🩺

#CONTRIBUTORS
Jarvan Okuro - javanokuro254@gmail.com 
Renard Owiti - renardowiti@gmail.com

# 
HealthTrack is a mobile-friendly web application designed to provide basic medical guidance and clinic referrals based on user-reported symptoms. Built for a hackathon focusing on SDGs 3 (Good Health & Well-being), 4 (Quality Education), and 11 (Sustainable Cities & Communities), its goal is to make preliminary healthcare advice more accessible and reduce unnecessary strain on medical facilities.

Live Demo: [https://health-aid-on-demand.lovable.app/]

https://via.placeholder.com/800x400?text=HealthTrack+Screenshot+Here

✨ Features
Symptom Logging: Users can easily input and describe their symptoms.

AI-Powered Advice: Receive basic, non-diagnostic medical guidance based on common knowledge.

Smart Referrals: Get recommendations for nearby or relevant clinics or hospitals if professional care is advised.

Private History: Maintain a secure, personal history of all your symptom logs and the advice given.

User Authentication: Secure sign-up and login to keep all health data private.

🛠️ Tech Stack
This project was generated with and built using a modern, full-stack toolkit:

Frontend Framework: Next.js / React

UI & Styling: (Lovable's default, likely Tailwind CSS)

Backend & Database: Supabase

PostgreSQL Database

User Authentication

Row Level Security for data protection

Development Platform: Lovable AI 

Deployment: Via Lovable



# 🚀 Getting Started
Prerequisites
A modern web browser.

A Supabase account (for running the setup scripts).

Installation & Setup
This project was generated with Lovable AI. To run it locally or contribute:

Clone the Repository (If you've connected Lovable to GitHub):

bash
git clone [your-lovable-project-github-url]
cd healthtrack
Install Dependencies:

bash
npm install
# or
yarn install
Environment Variables:
Create a .env.local file in the root directory and add your Supabase keys from your project settings:

env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
Database Setup:

Navigate to the SQL Editor in your Supabase project dashboard.

Run the SQL schema provided in the project documentation (database_setup.sql) to create all necessary tables and security policies.

Run the Development Server:

bash
npm run dev
# or
yarn dev
Open http://localhost:3000 with your browser to see the result.

📋 How to Use
Sign Up / Log In: Create a secure account to start using HealthTrack.

Log Symptoms: Navigate to the "Checkup" page and describe how you're feeling.

Get Advice: Submit your symptoms to receive basic guidance and see if a clinic referral is recommended.

Review History: Check your "History" page to see a log of all your previous check-ins and the advice given.

#🎯 Hackathon Focus: SDGs 3
SDG 3: Good Health & Well-being: Democratizes access to basic health information, promoting preventative care and informed decision-making


#🔮 Future Roadmap

More sophisticated AI analysis for symptom checking.

Medication tracking and reminder features.

Multi-language support to increase accessibility.

Push notifications for follow-up check-ins.

⚠️ Important Disclaimer
HealthTrack is a hackathon project and not a certified medical device. It is intended for informational purposes only and does not provide medical advice, diagnosis, or treatment. Always seek the advice of a qualified healthcare provider with any questions you may have regarding a medical condition. Never disregard professional medical advice or delay in seeking it because of something you have read on this application.
