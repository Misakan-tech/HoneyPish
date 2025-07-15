# HoneyPish
A web platform for vendor cybersecurity assessment and phishing awareness training, featuring automated risk scoring, dual-role dashboards, interactive phishing simulations (HoneyPhish), evidence upload, and real-time analytics — built with React, Node.js, PostgreSQL, and a modern 3D UI.          Ask ChatGPT
HoneyPhish Platform is a complete web application designed to help organizations assess third-party vendor cybersecurity posture and provide phishing awareness training through interactive simulations.

Core Features:
Dual Role Login System:
Separate, secure login flows for Vendors and Admins with role-based dashboard access.

Vendor Self-Assessment Portal:
Vendors fill out cybersecurity assessment forms covering HTTPS, MFA, encryption, breach history, and more. Automated risk scoring generates a Trust Score based on weighted responses.

Admin Dashboard:
View all vendors, filter by risk level, request fixes, and analyze risk data with real-time graphs and activity logs.

HoneyPhish Module:
An immersive phishing simulation experience where vendors interact with a fake inbox. Vendors report or click on phishing emails, affecting their scores and earning badges through gamification.

Gamification & Leaderboards:
Vendors earn Trust Scores and ranks like Platinum, Gold, Silver, and Bronze. Leaderboards foster engagement and promote continuous cybersecurity learning.

Evidence Upload & Third-Party Checks:
Vendors can upload security documentation, with API integrations like SSL Labs and HaveIBeenPwned for additional verification.

AI Chatbot Integration:
Built-in AI assistant for real-time cybersecurity guidance (using OpenAI GPT API).

Tech Stack:
Frontend: React + TypeScript, Tailwind CSS, Radix UI

Backend: Node.js + Express, PostgreSQL/Supabase

Authentication: Supabase Auth or JWT

3D Particle Background: tsParticles, Three.js

Charts & Graphs: Chart.js
