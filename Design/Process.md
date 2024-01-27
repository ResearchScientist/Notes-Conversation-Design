- make intents
- write replies
- deploy bot

```mermaid
flowchart LR
A(voice) -->
B(ASR) -->
C(transcription) -->
D(NLU) -->
E(intent)
```

# Workflow

Requirements
- tech available (feasibility)
- use cases, user journeys (problem to solve)
- users
- bot persona
Happy Flow
- happy path
Detailed Flow
- model training
- long tail
- exceptions
- repair

# Happy Path

```mermaid
flowchart TD
A(use scenario) --> 
B(user needs) & C(bot needs) --> 
D(sample dialogue) --> 
E(dialogue flowchart) --> 
F(woz) & G(copy edit) -->
H(refined dialogue)
```

# Scene

Describe the context

- location
- social
- temporal

# Needs

## User

goals
- wants to { }
- wants to know { }
mindset
- motivated by { }
- worries about { }
- expects { }
- feels { }
- assumptions

## Bot

powers
- can do
- can't do
- existing knowledge base
- can find out
responsibilities
- must ask { to decipher intent }
- must tell
- promotes
- discourages

