# ArgBot

# Users involved

- Catija (has the problem)  
- Petter (Lead)
- rene (I offered this crazy option, so now I feel responsible)
- Yvette (offered to help in development)
- Ashish Ahuja (offered to help in development)

# Goal
The bot will watch incoming comments and when they are posted on inactive posts, the comment will be posted in a chatroom

# Business case

https://meta.stackexchange.com/questions/301846/what-solutions-do-moderators-have-to-prevent-argumentative-comments

# wild idea's

- is it just like Petter describes: any comment on an old post? Because on your MSE post I got the idea that you were more looking for an option to find comments that are likely to derail a thread?
The former is kind of easy, the latter needs some form of intelligence

- Yeah if you like to use machine learning it gets a bit more complex but maybe (I don't have experience in your site), the traffic is low enough to just output all new comments on old posts in chat (FYI you better ping in this chat, with all these bot and people working it's hard to find messages)

- We create a dedicate bot in Java/Python to monitor these comments and post them to chat

- we create something which just monitors old comments and posts them on a ws; I already have a bot to monitor the ws.
The advantage of using PulseMonitor will be that we won't have to worry about the chat side.

We might branch off 
- Heat Detector   
- [Citation-Detector](https://github.com/SOBotics/Citation-Detector)  
- https://github.com/Fortunate-MAN/PulseMonitor  

Implementation languages offered so far: Java, Python, C#
 
