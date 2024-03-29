# Over Answering

Over answering refers to the user providing more information than requested.

Bot should be able to capture additional information given by a user when the bot asks a question.

Poor Experience

| bot | user |
| ---- | ---- |
| What size would you like? | A large in yellow. |
| You want a large. In what colour? |  |

Have bot store additional details within the captured context for later retrieval.

# Under Answering

In under answering the user provides less information than the bot expected.

| bot | user |
| --- | --- |
| When do you want to go on your trip? | next week |

Bot needs to be clearer and more specific with its questions to avoid under answering.

| bot | user |
| --- | --- |
| When do you want to go on your trip? For example, you can say "friday to monday" or "starting on feb 2 until feb 12". | I want to go next week from monday to wednesday. |

# Repeat

Capture utterances that indicate that the user did not understand the response given by the bot.

- huh
- what
- sorry
- I don't get it

Then have the bot provide a new response that is clearer and a variation of the initial response. Do not just repeat the same response to the user.

# Lengthy Responses

If the response is very long provide first a TLDR with an option for the user to choose more details.

Offer option as a
- button
- message prompt

