# ArgBot
Bot detecting new comments on old posts


# Goal
The bot will watch incoming comments and when they are posted on inactive posts, the comment will be posted in a chatroom

# Business case

https://meta.stackexchange.com/questions/301846/what-solutions-do-moderators-have-to-prevent-argumentative-comments

# wild idea's

- is it just like Petter describes: any comment on an old post? Because on your MSE post I got the idea that you were more looking for an option to find comments that are likely to derail a thread?
The former is kind of easy, the latter needs some form of intelligence

- Yeah if you like to use machine learning it gets a bit more complex but maybe (I don't have experience in your site), the traffic is low enough to just output all new comments on old posts in chat (FYI you better ping in this chat, with all these bot and people working it's hard to find messages)

We might branch of either Heat Detector or [Citation-Detector](https://github.com/SOBotics/Citation-Detector)
