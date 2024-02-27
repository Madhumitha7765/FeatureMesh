# FeatureMesh Chatbot documentation

## Overview

The Feature Mesh Chat Bot is a conversational interface designed to facilitate interactions with the Feature Mesh platform. It provides data engineers and data scientists with a convenient way to to know more about the portal and its functionalites, it also assists the data scientist in fetching the feature set from the portal.

## Functions of chat bot

- Helps the user to know more about the portal and its functionalities
- Assists the user in fetching the feature set from the portal
- Provides the user with the list of file formats supported by FeatureMesh
- The aim of this chat bot is to help & assist the user in getting data they need.
- The chat bot will be beneficial in the scenarios where the user cannot comprehend the UI elements of the web portal or is not able to find the required information.

## Example of chat bot usage

```text
Bot: Hello! How can I help you today
User: I needed help with knowing about what is meant by feature selection
Bot: Feature selection is the process of selecting a subset of relevant features for use in model construction
User: Ok
Bot: Is there anything I can help you with?
User: Sure, What all file formats are supported by FeatureMesh
Bot: FeatureMesh currently supports csv,xlsx
User: Ok, Thank you for your assistance
Bot: Happy to help! Is there anything else I can help you with?
User: No
Bot: Goodbye
```

## Functional Requirements of the chat bot

- Natural Language Processing (NLP) to understand the user's query
  - The chat bot should be able to understand the user's query and provide the appropriate response.
  - Each user can convery their requirements in different way, the bot should be able to understand their requirements.
- Error Handling
  - Any type of error can occur when serving user's request, the bot should be able to handle the errors and provide the user with the appropriate response.
- Personalization
  - The bot should be able to provide the user with the personalized response based on the user's query.
  - The bot should be able to provide the user with the personalized response based on the user's previous interactions with the bot.