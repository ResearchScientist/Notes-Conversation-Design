Project Management Cycle

- Strategy
- Validation
- Roadmap
- Backlog
- Research
- Design
- Development
- Test
- Measure KPIs and OKRs
- Revisit Strategy

# Discover Insights

Define the business

- goals
- expectations
- challenges
- strategy

Define the user's

- needs
- wants
- pain points

To define the above use

- journey maps
- empathy maps
- personas
- surveys

Document the insights for a specific scenario.

**Example**
User wants to make an appointment.

| business needs | user needs | tech needs |
| ---- | ---- | ---- |
| more staff | make an appointment | database |
| triage | reschedule appointment | APIs |
|  | cancel appointment | privacy |
|  | fast process |  |

# Discover Solutions

Ideate solutions

- what ifs
- how may we

Align business needs with user needs to come up with user stories.

# Scenarios

Identify what goals the user may have.
Then consider what content and processes you will need in order to meet those goals.
What resources will those processes require.

Usage Scenario

| User Goal | Content | Resources |
| ---- | ---- | ---- |
| make an appointment | - available hours<br>- triage | - scheduling system<br>- API |
| triage | - how to triage<br>- what is the criteria | - logic<br>- database<br>- privacy |
| reschedule |  |  |
| cancel appointment |  |  |
# Strategize

Goals
Questions 
KPIs

| (business)<br>Increase efficiency | (user)<br>fast appointment | (product)<br>automatic process |
| ---- | ---- | ---- |
| - how many users<br>- how many inquiries sent to human agents | - how many dropped off<br>- how many transferred to human agent<br>- duration of interaction | - AI performance<br>- success rate |
| - n users<br>- utilization rate<br>- deflection rate | - resolution rate<br>- average interaction duration<br>- bounce rate<br>- handover rate<br>- effort score | - n issues<br>- average success rate |

Additional KPIs

- agent utilization rate
- bounce rate
- conversion length (average)
- conversion volume
- deflection rate
- execution time (average)
- FAQs (most frequent)
- handover rate
- intent scores
- intent trainer (new training phrases)
- misunderstood phrases vs understood phrases (rate)
- n issues
- n users
- resolution duration (average)
- resolution rate
- top used intents (most frequently asked questions)
- user effort score

# Priority

Methods to determine priority.

- value vs effort
- [[#Value vs Effort]]
- [[#Weighted Scoring]]
- kano
- story mapping

## Value vs Effort

You want to aim for high value and low effort solutions

|  |  |  |
| ---- | ---- | ---- |
| high value | x |  |
| low value |  |  |
|  | low effort | high effort |
Write solutions on stickies and place along the board based on their respective value and effort.

```mermaid
xychart-beta
	title "value vs effort"
	x-axis "effort" 0 --> 10
	y-axis "value" 0 --> 10
	line [0,10]
```

## Weighted Scoring

To avoid biasing business needs over user needs use a weighted score.

weighted score = (value) / (effort)

## Steps

- Place stickies along effort vs value graph.
- Prioritize those items that are of highest value and low effort.

# Measures

- identify the step where the user dropped off or had an issue
- did the user reach their goal
- user satisfaction , question at end of interaction, did the bot help you, did you achieve your goal, was your experience pleasant, why, anything you would like to say

# Metrics

Measure 
- understanding
- decision making
- conversation

convos = total n conversations received
escalations = n conversations sent to live agent
success = n successfully resolved conversations

`handover rate = (escalations) / (convos)`
`deflection rate = (convos - escalations) / (convos)`
`resolution rate = (success) / (convos)`
`resolution duration (ave) = (sum of all convos durations) / (convos)`
`user effort score = survey`
`bounce rate = some threshold`

