# secure-serverless-chat-client

This single page application is a chat app built using Vue.js that uses the MSAL.js library to authenticate against an Azure AD B2C directory.

The real-time chat functionality is provided by the Azure SignalR service. Web socket connections are negotiated via a serverless api gateway (Azure API Management Service in consumption mode).

This project is the client (single page application) part of the Solution Architecture diagram. The Function App code can be found [here](https://github.com/mattburrell/secure-serverless-chat-api).

![](https://github.com/mattburrell/secure-serverless-chat-client/blob/master/Secure%20Serverless%20Chat.jpeg)
