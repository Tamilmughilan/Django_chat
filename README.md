# Django Chat Application

A simple and feature-rich chat application built using Django, featuring user authentication, CRUD operations, WebSockets, and real-time messaging.



## Features 
- CRUD operations for users (Create, Read, Update, Delete)
- Create and join chat rooms, and engage in group chats
- User-friendly, responsive UI
- WebSocket integration for real-time communication
- Authentication for WebSockets to prevent unauthorized access
- Profile management with username and profile picture
- Persistent message storage in the database

## Setup 

### 1. Clone the repository
Clone or download the repository to your local machine.

```bash
git clone https://github.com/Tamilmughilan/Django_chat.git
cd Django_chat_project
```

### 2. Create and activate a virtual environment

For **Windows**:

```bash
python -m venv venv
venv\Scripts\activate
```
3. Install required packages
```bash
python -m pip install -r requirements.txt
```

4. Navigate to chat-app-django and run the server
```bash
python manage.py runserver
```
*Note: make migrations if any error occurs*
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Navigate to http://127.0.0.1:8000 on a browser of your choice.

