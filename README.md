# Create WhatApp Chatbot💬 using ChatGPT, Flask, and EC2
<source src="https://github.com/iwinster/whatsappbot/blob/7b4688c580b8e913bfcdf3c2e991c9c1fe215aa8/WhatsApp%20Video%202023-06-12%20at%201.25.10%20PM.mp4" type="video/mp4">

## We have used:
- Ngrok and Flask as a server.
- Twilio as whatsapp agent.
- ChatGPT API for generating response.
- Flask App as API for Request/Response model.
- AWS EC2 for deployment (24/7 running). 

## Steps
1. Create free account in [openai](https://platform.openai.com/account/api-keys), [Twilio](https://console.twilio.com/), [AWS](https://console.aws.amazon.com/), and [Ngrok](https://dashboard.ngrok.com/).
2. Open twilio console, register your whatsapp number. 
3. Create Flask App.
4. Launch EC2 in AWS.
5. Install requirements in EC2.
6. Setup credentials(OpenAI and Ngrok) in EC2.
7. Run Flask App in EC2.
8. Run Ngrok on same port as Flask App. 
9. Setup Ngrok URL in Whatsapp Sandbox (in Twilio console).
10. Done, chatbot is activated!!

## Usage:
- Clone my repository.
- Open CMD in working directory.
- Run following command.

  ```
  pip install -r requirements.txt
  ```
- `BOT_API.py` is the Flask API which handles Request/Response of ChatBOT.
- To run this script follow this command.
  ``` 
    python3 BOT_API.py
  ```

