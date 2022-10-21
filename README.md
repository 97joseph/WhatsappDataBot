# WhatsappDataBot
Data Rules Guidance  System

The task consist in two steps 

Step 1 

-Create api with auto answer button, bold, italic, underline and emoj text function.
-Configure Qrcode with whatsapp, allow all functions to work well by generating Qrcode only once. 

Step 2 

-Create Dashboard to Manage User Licenses - Allow License Lock if User Late Payment or Cancel Subscription. Improve performance (allow software to be faster and lighter)
 

QR Code : 

To send messages user need to activate the QRcode to connect to whatsapp. For the chatbot function to work, it is also necessary to activate the Qrcode. In other words, if The Client is sending a message, the chat bot doesn't work. So The Client need the chatbot to work even when The Client sending messages. Chatbot should stop working only when The Client create a new rule.

# WhatsApp Pseudo Bot

Simple python3 class that lets you send messages through browser automation (Selenium).

## Getting Started

To use this class you must have Selenium:

    pip install -U selenium
You also need to have the browsers driver (Chrome by default). You can change the default driver in the class initializer. You can get the Chrome driver [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).
Finally, you can find the class in `wp_bot.py`.

