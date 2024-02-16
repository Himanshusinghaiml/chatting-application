#made by Himanshu Singh 

A private messaging and calling application build using Django, Django Channel and Peer.js (WebRTC).
The front end has been build in Vue.js and I use Django Rest Framework for communicate with Backend and Frontend.  

PyWebsocket is been used inside Django Channel Wrapper for realtime communication. 
WebRTC is been used for Video and Audio calling.

### FrontEnd Installation
```
cd frontend
npm install
npm run dev
```

### Backend Installation
```
cd server
pipenv shell
pipenv install
python manage.py migrate
python manage.py runserver
 