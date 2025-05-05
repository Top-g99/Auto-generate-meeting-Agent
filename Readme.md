# Auto-Generated Meeting Attendee Research  
**Powered by GPT-4o, Google Calendar, and Gmail**

> Instantly get meeting briefings with attendee and company info every time a new event is added to your Google Calendar — researched using GPT-4o and delivered via Gmail.

---

## 🧩 Overview
- Triggers when a new event is added to Google Calendar  
- Uses GPT-4o with web search to research each attendee and their company  
- Sends a compiled briefing to your inbox before the meeting  

---

## ⚙️ Features
- Calendar event trigger  
- Web-based attendee and company research  
- GPT-4o-generated summaries  
- Email delivery to a selected address  

---

## 🔧 Setup

### 1. Connect APIs
- Google Calendar → Read access  
- Gmail → Send access  
- OpenAI → GPT-4o with web search enabled  

### 2. Auth Headers for OpenAI API
Name: Authorization
Value: Bearer {{YOUR_API_KEY}}

yaml
Copy
Edit
### 3. Configure "Edit Fields" Node
- Input recipient email  
- Add a short bio/context about yourself  

---

## 📬 Email Briefing Includes
- Attendee names and roles  
- Background summaries (from web and LinkedIn)  
- Company details and recent updates  

---

## ✅ Requirements
- Google account  
- OpenAI API key (GPT-4o with browsing access)  
- Automation platform (e.g. n8n, Make, or custom script)

---

## 💼 Use Cases
- Sales & client calls  
- Investor meetings  
- Interview prep  
- Team syncs with new participants
