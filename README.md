# MedBot-Pro

MedBot Pro – AI Health Assistant

Case Study & System Documentation
by Lee Natividad – AI Agent Engineer | AI Specialist

1. System Overview

MedBot Pro is an AI-powered healthcare assistant built using Jotform AI Agent Builder, designed to provide 24/7 patient interaction, triage, and specialist recommendations.

It combines AI-driven natural language processing (NLP) with automated hospital workflows such as:

Symptom triage

Appointment scheduling

Specialist referral

Real-time emergency detection

Patient communication (Chat + Call)

This system acts as the frontline AI assistant for hospitals and clinics, reducing the workload of healthcare staff and improving patient response times.

2. Objectives

The MedBot Pro project was created to address common hospital challenges:

Patient Overload – Many inquiries, limited front desk staff.

Triage Efficiency – Need for faster classification of urgent vs. non-urgent cases.

24/7 Availability – Patients expect healthcare access anytime.

Digital Integration – Hospitals need automated systems connected to bookings, calendars, and medical databases.

3. Core Features
Patient Interaction

Chat-based mode: Text conversations with patients

Voice & Call mode: Phone/voice AI integration

Standalone Web App: Patients can access without installing anything

AI Triage & Health Guidance

Symptom analysis and possible cause detection

Emergency detection (e.g., chest pain → immediate ER referral)

Personalized guidance based on patient inputs

Appointment Scheduling

Integrated with Jotform Appointment Forms

Auto-suggests specialists based on symptoms

Sends confirmations and reminders via email/SMS

Specialist Recommendation

Conditional logic mapping for 40+ medical specialists

Example mappings:

Chest pain → Cardiologist

Skin rash → Dermatologist

Blurry vision → Ophthalmologist

Workflow Automation

Integration-ready with n8n or Zapier for advanced tasks:

Auto-log patients into Google Sheets / Airtable

Send PDF case summary via email

Trigger emergency alerts to doctors

4. System Architecture
[Patient] 
   ↓ Chat / Voice
[MedBot Pro – AI Agent] 
   ↓
[Triage + Specialist Mapping Engine] 
   ↓
[Appointment System + Emergency Alerts] 
   ↓
[Hospital Database / Google Sheets / n8n Automation]


Frontend: Jotform AI Agent (Standalone + Chatbot + Call)

Backend: Jotform Form Logic + n8n Automations

Data Flow:

User enters symptoms

AI analyzes and suggests next steps

If booking required → forwards to Jotform Appointment Form

Logs data to external systems (Sheets, CRM, Database)

5. User Experience (UX) Flow

Patient enters symptoms (via chat or voice)

AI responds with triage assessment (mild, urgent, emergency)

Specialist suggestion is displayed (e.g., Neurologist)

Patient books an appointment through the integrated form

System auto-sends confirmation and reminders

Hospital staff receives case data (PDF/Sheets)

6. Deployment Channels

Standalone Web App (shareable link)

Chatbot Embed (clinic website, social media messenger)

Voice & Phone Integration

Mobile App (PWA) – installable version of Jotform App

7. Benefits

Reduces patient wait time

Ensures correct specialist referral

Works 24/7 with zero human fatigue

Scalable across multiple hospital departments

Can handle thousands of patients simultaneously

8. Future Enhancements

EHR (Electronic Health Records) integration

AI-powered follow-up reminders (post-surgery care)

Wearable integration (Fitbit, Apple Watch health alerts)

Multilingual support (Tagalog, English, Chinese, etc.)

9. Screenshots & Visuals

(to be included from your Jotform preview, chatbot interface, and triage flow examples)

10. Conclusion

MedBot Pro demonstrates how AI and automation can reshape hospital frontlines.
By combining symptom triage, specialist mapping, and appointment scheduling into one seamless AI system, MedBot Pro represents the future of digital healthcare assistance.

It is not just a chatbot—it is an AI-powered medical triage system that can scale with hospitals, clinics, and healthcare providers worldwide.
