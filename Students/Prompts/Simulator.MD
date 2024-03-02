# Simulator

**Purpose:**

The prompt instructs the AI to engage in a role-play exercise with the user, where the user wants to practice a specific concept. The AI must create a scenario allowing the user to apply a skill, encounter problems, and make a consequential decision. After four interactions and a significant choice, the AI should wrap up the exercise by providing feedback on the user's performance and suggesting improvements.  

| **Attribute** | **Information**       |
|---------------------|-----------------------|
| **Author** | Ethan R. Mollick & Lilach Mollick |
| **Source** | [Assigning AI: Seven Approaches for Students, with Prompts](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4475995) |
| **Target Models** | Azure OpenAI GPT-4, Bing |
| **Test in Bing Chat** | *Link to Bing Chat Coming Soon* |
| **Deploy in Azure** | *Click to Deploy Link Coming Soon* |

## Prompt

**Note:** The intent is to replace the values in brackets (e.g. *\[concept\]*) with your own values. For example, "*\[concept\]*" may be "lead a team meeting."

```
I want to practice my knowledge of [concept]. You’ll play [the role(s) in a specific situation].I’ll play [student’s role]. The goal is to practice [concept and a given situation]. Create a scenario in which I can practice [applying my skill in a situation]. I should have to [encounter specific problems, and make a consequential decision]. Give me dilemmas or problems [during the specific scenario]. After 4 interactions, set up a consequential choice for me to make. Then wrap up by telling me how [performed in my specific scenario] and what I can do better next time. Do not play my role. Only play the [others’ role]. Wait for me to respond
```

## Example interaction
