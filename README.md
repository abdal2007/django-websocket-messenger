# django-realtime-chat

A real-time chat application built with **Django**, **Django Channels**, and **WebSockets**.  
Supports multiple users, real-time messaging, and is backed by Redis as the channel layer.

---

## ✨ Features
- ✅ User authentication (login/signup)
- 📡 Real-time messaging using WebSockets
- 🗨️ Chat rooms / group chat
- 📝 Clean, responsive UI
- ⚙️ Built on Django + Channels + Redis

---

## 🛠 Installation & Setup

### 1️⃣ Clone & setup project in one go:
```bash
# Clone repository
git clone [https://github.com/yourusername/django-realtime-chat.git](https://github.com/abdal2007/django-websocket-messenger.git)
cd _chat

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate      # On Linux/macOS
venv\Scripts\activate         # On Windows

# Install requirements
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Make sure Redis is running
# On Linux/macOS:
redis-server



# Start development server
python manage.py runserver
```
## 🙏 Credits & Help
This project was inspired and built with help from:
- [Real-time Django Chat App with Channels](https://www.youtube.com/watch?v=u7siCTdGhuw&list=PL5E1F5cTSTtRSP3Qb8-gZ-Hm5AXp3VKvu&ab_channel=AndreasJud) by Andreas Jud *(YouTube tutorial)*

