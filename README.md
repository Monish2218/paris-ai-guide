# paris-ai-guide
A virtual Parisian expert, delivering valuable insights into the city's iconic landmarks and hidden treasures.

You'll create a chatbot using the OpenAI API to generate responses to the following Parisian tourist questions:

How far away is the Louvre from the Eiffel Tower (in miles) if you are driving?
Where is the Arc de Triomphe?
What are the must-see artworks at the Louvre Museum?
Create a list of dictionaries called conversation that lists the 'role' and 'content' for each question and response. You should start the conversation with a 'system' message to set the model's behavior, and use a temperature of 0.0 and maximum number of tokens of 100:
[ {"role": "system", "content": ...}, {"role": "user", "content": ...}, ... ]

As a distinguished AI Developer, you've been selected by Peterman Reality Tours, an internationally acclaimed tourism company, to undertake an influential project. This project requires you to harness the potential of OpenAI's API, specifically using its state-of-the-art language model, GPT-3.5 Turbo, to create an AI-powered travel guide for the culturally rich city of Paris.

Your creation will become a virtual Parisian expert, delivering valuable insights into the city's iconic landmarks and hidden treasures. The AI will respond intelligently to a set of common questions, providing a more engaging and immersive travel planning experience for the clientele of Peterman Reality Tours.

The ultimate aspiration is a user-friendly, AI-driven travel guide that significantly enhances the exploration of Paris. Users will be able to pre-define their questions and receive well-informed answers from the AI, providing a seamless and intuitive travel planning process.

Before you start
In order to complete the project you will need to create a developer account with OpenAI and store your API key as an environment variable. Instructions for these steps are outlined below.

Create a developer account with OpenAI
Go to the API signup page.

Create your account (you'll need to provide your email address and your phone number).

Image from the file system
Go to the API keys page.

Create a new secret key.

Image from the file system
Take a copy of it. (If you lose it, delete the key and create a new one.)
Add a payment method
OpenAI sometimes provides free credits for the API, but this can vary based on geography. You may need to add debit/credit card details.

Using the gpt-3.5-turbo model in this project should incur a cost less than 1 US cent (but if you rerun tasks, you will be charged every time). For more information on pricing, see OpenAI's pricing page.

Go to the Payment Methods page.

Click Add payment method.

Image from the file system
Fill in your card details.
Add an environment variable for your OpenAI key
In the Workbook, click on "Environment," in the left sidebar.

Click on the plus button next to "Environment variables" to add environment variables.

In the "Name" field, type "OPENAI". In the "Value" field, paste in your secret key.

Image from the file system
Click "Create", then you'll see the following pop-up window. Click "Connect," then wait 5-10 seconds for the kernel to restart, or restart it manually in the Run menu.
Image from the file system

