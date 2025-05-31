## Challenge: Sanity Check

### Description

This HackTheBox Discord challenge involves finding a hidden flag through interaction with a bot in a private server channel. The challenge name suggests verifying what’s real—a "sanity check"—which ties into evaluating the usefulness of various commands.

### Process

While browsing the available Discord channels, one stands out: a hidden one named `#lame-bot`. Despite being private, it is possible to send messages in it. Reviewing the channel's message history suggests this is the correct location for bot interaction.

![Image](path/to/image.png)

By typing `/` in the chat, you can explore the available commands under the **Hack The Box** command group. Among them:

- `/hint` offers vague or misleading guidance.
- `/random`, on the other hand, returns an unexpected result.

Using `/random` in `#lame-bot` triggers a response that reveals the flag.

![Image](path/to/image.png)

