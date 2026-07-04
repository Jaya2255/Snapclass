# SnapClass – AI-Powered Attendance System

An end-to-end full-stack attendance tracking system designed to automate classroom rosters using computer vision and voice biometrics. It features a responsive Flask portfolio landing page that seamlessly routes users to an interactive Streamlit application dashboard.

## 🚀 Core Features
* **Biometric Authentication:** Uses FaceRecognition (Dlib) and voice embeddings to securely identify individuals.
* **Real-Time Database:** Integrated with Supabase Cloud (PostgreSQL) for instant student enrollment and roster tracking.
* **Dynamic QR Engine:** Generates real-time, dynamic QR codes for swift automated check-ins.
* **Analytics Dashboard:** Generates actionable tracking trends and lets instructors export detailed attendance reports as CSV files.

## 🛠️ Tech Stack
* **Frontend Showcase:** Flask, HTML5, CSS3 (Deployed via Vercel)
* **Core Application Platform:** Streamlit (Deployed via Streamlit Community Cloud)
* **Database Backend:** Supabase Cloud / PostgreSQL
* **ML & AI Frameworks:** FaceRecognition, Resemblyzer

## 📦 Project Structure
* **`SC-landing-page` Repository:** Holds the responsive Flask landing page and UI styles deployed on Vercel.
* **`Snapclass` Repository:** Holds the main interactive core application logic, biometric pipelines, and database connections.
