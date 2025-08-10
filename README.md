🍳 Recipe Agent – IBM watsonx.ai
---------------------------------

📖 Overview
------------

- The Recipe Agent is an AI-powered assistant built using IBM watsonx.ai’s Agent Lab and Python API.
- It demonstrates how to configure, authenticate, and interact with a LangGraph agent to answer recipe-related queries based on available ingredients.
- This project combines IBM Cloud Watson Machine Learning, LangGraph, and custom tool functions to create a conversational agent that can:
- Search and recommend recipes.
- Suggest substitutions for missing ingredients.
- Provide step-by-step cooking instructions.

⚠️ This project was developed and executed in the IBM watsonx.ai Agent Lab environment.
Modifying the generated code may affect its ability to run successfully.

--------------------------------------------------------------------------------

🎯 Features
------------

Ingredient-based Recipe Search – Ask the agent what you can cook with what you have.

Cooking Instructions – Get easy-to-follow steps for your chosen recipe.

Substitution Suggestions – Learn how to replace unavailable ingredients.

Cloud-Ready – Built with IBM watsonx.ai, deployable on IBM Cloud.

---------------------------------------------------------------------------------

🛠 Tech Stack
-------------

Language: Python 3.11

Platform: IBM watsonx.ai Agent Lab

Libraries:
ibm_watsonx_ai
langgraph
ibm_cloud_sdk_core
requests

Data: CSV-based recipe dataset (customizable)

----------------------------------------------------------------------------------

📊 Workflow
------------

Authenticate with IBM Cloud using your API key.

Initialize the Agent with LangGraph and custom tools.

Process User Query – Pass ingredients or cooking questions.

Generate Recipe – Fetch and display recipe recommendations.

----------------------------------------------------------------------------------

📌 Example Usage
-----------------

User: "I have tomatoes, pasta, and cheese. What can I make?"
Agent: "You can make Tomato Cheese Pasta. Here’s how..."

------------------------------------------------------------------------------------
Thank You!
