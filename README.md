# AnokhaBot
A contextual Chatbot that anyone can use to learn more about Anokha

## Requirements
1. TensorFlow
2. telepot
3. A Telegram account (Only if you wanna deploy it on Telegram)

## Testing
If you want to test out a version of this Bot, download telegram and search for AnokhaBot

## Features
This chatbot figures out the context from what you type in and chooses a reply from one of the replies that are pre-built. I've implemented a very basic error loging system wherein if the bot replies incorrectly, it will be logged and can be later added to the training data to make it better.

## To Be Implemented
- [ ] Registration for events through the chatbot
- [ ] Making replies autonomous(no more pre-built replies)

## Disclaimer
The training data (context.json) keeps increasing as the number of users increase. Given that we are college students (pretty immature) I had to include two separate categories cuss and sexual advances from the large number of queries pertaining to these areas. Basically, you can choose not to include the cuss words and sexual advances, I have included the cleanContext.json for that purpose.