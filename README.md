# 📞 AI Voice Assistant using VAPI + SIP

This project is an online voice assistant that works over SIP calls using [VAPI](https://www.vapi.ai/) and a free SIP client (Linphone). The assistant can help users check if they qualify for a mentorship program by having a real-time conversation.

---

## 🚀 Features

- Free SIP-based phone assistant
- VAPI integration for AI responses
- Works with Linphone app
- Speech-to-text + text-to-speech
- No paid number required for demo

---

## 🛠️ How to Run Locally

1. Clone the repo

```bash
git clone https://github.com/nehaaaak/ai-voice-assistant.git
cd ai-voice-assistant
```

2. Set up a free SIP account (e.g., from linhome or similar)

3. Log into VAPI Dashboard

  -Set up a new assistant

  -Choose "SIP" integration

  -Copy the generated SIP URI as the inbound number

4. Install Linphone

  -Add your SIP account

  -Dial your Vapi SIP number (e.g., sip:your-assistant-id@sip.vapi.ai) to start the conversation

  -Talk to your assistant 🎙️

---

## 🔒 Limitations

-This project is demo-only with a free SIP account. It's designed to run locally.

-Only supports calling through SIP (e.g., Linphone) — not public phone numbers unless you buy a number.

-You can’t receive real calls from others unless you use a real phone number
