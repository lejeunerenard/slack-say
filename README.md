# Slack say

Pipe text to slack without an API Token. This is just a "proof of concept" / hack to make command line output easier to message over slack.

Currently only OSX is supported.

## Use
First make sure slack is open. Then pipe your text to slack-say:

```
echo 'Why hello there!' | slack-say
```

The text will be typed in the current message box followed by an enter press to send the message.
