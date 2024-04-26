# Node.js-Rest-API
this project is to create a Node.js application using Express and whatsapp-web.js to process messages through WhatsApp.


# whatsapp-web.js
A WhatsApp API client that connects through the WhatsApp Web browser app

The library works by launching the WhatsApp Web browser application and managing it using Puppeteer to create an instance of WhatsApp Web, thereby mitigating the risk of being blocked. The WhatsApp API client connects through the WhatsApp Web browser app, accessing its internal functions. This grants you access to nearly all the features available on WhatsApp Web, enabling dynamic handling similar to any other Node.js application.


Supported features
Feature	Status
Multi Device	✅
Send messages	✅
Receive messages	✅
Send media (images/audio/documents)	✅
Send media (video)	✅ (requires Google Chrome)
Send stickers	✅
Receive media (images/audio/video/documents)	✅
Send contact cards	✅
Send location	✅
Send buttons	❌ (DEPRECATED)
Send lists	❌ (DEPRECATED)
Receive location	✅
Message replies	✅
Join groups by invite	✅
Get invite for group	✅
Modify group info (subject, description)	✅
Modify group settings (send messages, edit info)	✅
Add group participants	✅
Kick group participants	✅
Promote/demote group participants	✅
Mention users	✅
Mention groups	✅
Mute/unmute chats	✅
Block/unblock contacts	✅
Get contact info	✅
Get profile pictures	✅
Set user status message	✅
React to messages	✅
Create polls	✅
Vote in polls	🔜
Communities	🔜
Channels	🔜
Something missing? Make an issue and let us know!
