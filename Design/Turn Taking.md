# Greeting

Have the bot initialize by
- introducing itself
- briefly stating what it's there for
- giving a simple example of how to interact with it , ie example of a question to ask it
- prompting to user to engage

# Goodbye

Have a clear indicator that the conversation has ended
- a sound
- a message

Capture user signals that they want to end the conversation.
Signals like the following should prompt the agent to end the conversation.

Positive
- ok goodbye
- i'm done
- thank you

Negative
- stop talking
- don't bug me
- stop
- go away
- leave me alone

For negative signals write copy that expresses the bot's acknowledgment of the user's frustration.

- sorry I was unable to help you, perhaps next time, Bye now

# Call To Action

End each bot message with a prompt for the user to act on.
Only prompt the user with 1 call to action per bot reply.

# Interrupt

Allow for a bot response to be interrupted by the user.
This is useful when the bot gives a response that is too long or is irrelevant.

Capture user utterances such as
- stop
- no
- try again

These should trigger the bot to rephrase the response as a TLDR or to ask for clarification from the user.

