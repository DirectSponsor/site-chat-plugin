Moving all our stuff to our own sever. Archiving it. 

# site-chat-plugin
Currently using Telegram for in-page chat which is able to be embedded via a bot into the site. It’s a plug-in and a bot called chatbro which is no longer maintained (2 years). The dev runs it on his own server which is often down, but we could run it ourselves using the open source code on github.

This is distincy from the jitsi chat with video conferencing, screen sharing etc. This is just a small, simple chat box to appear on the home page and maybe other pages where users can chat without having to to to a specific page and cope with all the choices that jitsi involves.

What we have used and worked well is a plug-in called chatbro which uses a telegram group as its base, and a telegram bot (chatbro) which enables users of the site to immediately start chatting without registering with either telegram or the chat group. Their site username is automatically used in the chat. We make the bot a member of the telegram group in order to do this.
