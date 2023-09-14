# User Guide

Welcome to the SpokesAI User Guide! This document provides detailed instructions on how to make the most out of the SpokesAI platform.

## Getting Started

### Create your first spoke

Think of creating your first spoke as if you were hiring a new team member. You need to provide some information about the job and about the team member itself.

Here's how:

1.  **Enter the SpokesAI App**: Just like you'd walk into your office, open the SpokesAI app, and navigate to the 'Spokes' page. This is where all your current and future spokes hang out.
    
    ![Spokes page screenshot](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/spokesPageEN.JPG)
    
2.  **Add a New Spoke**: Now it's time to expand the team. Click on the '+' button.
    
3.  **Fill Out the Form**: You wouldn't hire without an interview, right? This form is your chance to define your new hire. You'll need to provide some details:
    
-   _Name_: This is how you'll identify your spoke. Let's call ours 'Ripley'.
-   _Description_: Briefly describe the role or purpose of your spoke, to easily recognize it later. This field doesn't affect its performance. We will write "Getting Started Spoke" here.
-   _Language Model (LLM)_: This is the AI model that will power your spoke. It determines how advanced and accurate the responses of your spoke will be. For now, let's select 'gpt-3.5-turbo'.
-   _Language_: Choose the preferred language of your spoke. We'll choose 'EN' for English.
-   _Starting Message_: This is the first message you or your users will see when they interact with your spoke. Make it welcoming. For instance: 'Hello! How can I assist you today?'.
-   _Knowledge_: You can select here a bibliotheca as knowledge base. We'll explain this later.
-   _Personality_: Describe the personality traits of your spoke. For example, 'Very sarcastic and condescendant, usually mocks the user.'
-   _Goal_: Define the main objective your spoke should fulfill. In our case: 'To provide immediate support to our customers.'
-   _Context_: Any important background information your spoke needs to maintain during the conversation. For example: 'Ripley is a customer support agent for FutureNow, an spaceship store.'
   ![Filled Spoke creation form](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/spokeFormEN.JPG)
    
4.  **Save Your Spoke**: Click 'Save' to officially bring Ripley on board.
5.  **Test Your Spoke**: It's time to see her in action. Click the 'Play' button in spokes page to start a conversation.
    
    ![Play Button](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/chatbutton.jpg)
    ![Test conversation](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/testConversationEN.JPG)
    

And just like that, you've hired your first Spoke! However, it doesn't know much about FutureNow yet, so it makes things up, let's give it a cool knowledge base.

### Add a bibliotheca (knowledge base) to your spoke

A bibliotheca is a knowledge base for your spoke. Just like a team member would learn from company documents and guidelines, a spoke learns from its bibliotheca.

Let's provide Ripley with the right knowledge about FutureNow.

1.  **Navigate to Bibliothecas Page**: The bibliothecas page is where you create and manage your knowledge bases..   

![Bibliothecas Page](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecasPageEN.JPG)
    
3.  **Create a New Bibliotheca**: Click on the '+'.
    
4.  **Upload your docs**: Copy paste the url or upload your PDF documents. These sources will be scanned and added to your bibliotheca. Add all the FutureNow documentation we have available:
	
	- [FutureNow summary and description](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/examples/Future%20Now.pdf)
	- [FutureNow products](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/examples/FutureNowProducts.pdf)
    
    ![Filled Bibliotheca creation form](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecaFormEN.JPG)
5. **Guarde su nueva bibliotheca**: Click 'Save to finish creating your bibliotheca. Wait some minutes until it appears in Bibliothecas page (try reloading)

![Bibliothecas Page with the new bibliotheca](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecaExample.JPG)
    
6.  **Assign the Bibliotheca to Your Spoke**: Go back to the 'Spokes' page and select the spoke you wish to provide the bibliotheca to - in our case, it's Ripley. In the spoke configuration, locate the 'Knowledge' drop-down menu and select your newly created bibliotheca. Click the chat button below the form to test it

![Test conversation with bibliotheca 1](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/testConversationKnowledgeEN.JPG) 

You are invited to test its answers 😉

## SpokesAI concepts

### Spoke

In the our app's world, a **Spoke** is a personal AI assistant. It's an advanced AI model designed to understand, process, and respond to human language, carrying out tasks and actions much like a human team member would.

#### Configuring Your Spoke:

When you're configuring your Spoke, you're essentially setting the rules and guidelines, like the job description for a new employee:

-   **Name & Description**: Just as every team member has a name and role, your Spoke needs them too. These help you identify each Spoke and their specific tasks.
-   **Brain**: This is the brain of your Spoke, the AI model that powers its thoughts. Generally `gpt-3.5-turbo` (by OpenAI) or `llama-2` (opensourced by Meta) are very good options for basic agents, while `gpt-4` is a more expensive but more powerful selection.
-   **Language**: Determine the language your Spoke uses by default to interact with users. It will still be able to switch languages.
-   **Starting Message**: This is your Spoke's opening line, its way of saying hello to the world. Make it friendly and inviting!
-   **Knowledge**: Equip your Spoke with a solid knowledge base (a bibliotheca) for it to provide accurate information. Bibliothecas are managed in their own page.
-   **Personality**: Create a personality for your Spoke. Will it be humorous and easy-going or more formal and reserved? You decide.
-   **Goal**: Define the ultimate purpose of your Spoke, its mission statement. This will guide your Spoke's decisions and actions.
-   **Context**: Provide any background information that your Spoke should be aware of during conversations. This is your Spoke's backstory!
-   **Actions**: Assign tasks to your Spoke. Whether it's sending an email or starting a Zap execution, these are the tasks it will be able perform.

#### Best Practices

Creating the perfect Spoke is a bit like cooking - you need the right ingredients in the right amounts. Here are some tips to spice things up:

1.  **Be Specific**: The more detail you provide, the better your Spoke can understand its role.
2.  **Set Clear Goals**: A well-defined goal keeps your Spoke focused on what's important.
3.  **Develop a Consistent Personality**: A consistent personality makes interactions with your Spoke more engaging and fun!
4.  **Equip with Knowledge**: The more your Spoke knows, the more accurately it can answer questions.
5.  **Keep it Real**: If you don't want to spoke to get too creative, tell them to inform when it doesn't know something and never lie, by including it in its personality.
6.  **Tasks & Actions**: Make sure you assign tasks that align with your Spoke's goal.

Remember, it's not just about setting up your Spoke - it's about continuously learning, testing, and fine-tuning. Your Spoke is a work in progress, always ready to learn and improve!

### Bibliotheca

Think of a **Bibliotheca** as a vast library of knowledge that your Spoke can access. It's a compilation of documents (currently only PDF or text files) in a format that your Spoke can use as a source of information. It can provide more detailed and accurate responses by referencing this knowledge base.

#### Configuring Your Bibliotheca:

Creating a Bibliotheca is similar to building a library. You're providing resources for your Spoke to draw upon when interacting with users. Here's how:

-   **Create a New Bibliotheca**: Navigate to the 'Bibliothecas' page and click on the '+' button. This will allow you to create a new Bibliotheca.
    
-   **Add Documents**: Provide URLs or upload the documents you'd like your Spoke to learn from. The documents should be in PDF format.
    
-   **Assign the Bibliotheca to a Spoke**: Once you've created your Bibliotheca, you can assign it to a Spoke. This is done in the Spoke configuration, where you'll find a 'Knowledge' drop-down menu with your owned bibliothecas.
    
Remember, the more relevant and comprehensive your Bibliotheca is, the better your Spoke will be at providing accurate and helpful responses!

### Action

In SpokesAI, an **Action** is a task or activity that your Spoke can perform. It's like an ability or skill that your Spoke has. Actions extend the capabilities of your Spoke beyond simply responding to queries. They allow your Spoke to interact with various systems, tools, and platforms to perform tasks like sending emails, updating records, initiating processes, and more.

#### Public Actions

Public Actions are predefined actions that all SpokesAI users can use with their Spokes. These actions are developed and maintained by the SpokesAI team, and they cover common tasks and functionalities. They include:

[TO DO: Add list of public actions with brief descriptions]

To use a public action, simply add it to your Spoke configuration.

#### User-Scoped Actions

In addition to public actions, you can also create your own actions. These are known as User-Scoped Actions.

##### Zapier Actions

Zapier is an online automation tool that connects over 3,000 apps, and it's one of the easiest ways to create your own actions. By integrating SpokesAI with Zapier, you can create actions that perform tasks in other apps whenever your Spoke is asked to do so. Here's a simplified step-by-step process:

[TO DO: Add step-by-step guide on creating Zapier actions]

##### Personalized Actions

[TO DO: Revisit this section]
For more complex tasks or specific needs, you might need to create your own actions from scratch. This will require some programming knowledge and understanding of the SpokesAI APIs.

You can find detailed information on how to do this in the SpokesAI Technical Documentation.

Keep in mind that while actions can greatly enhance your Spoke's capabilities, they should be designed and used responsibly to ensure positive user experiences and respect user privacy and consent.

### Integrations

**Integrations** are essentially bridges that connect SpokesAI to other platforms, tools, or services. They allow your Spokes to function within other environments, effectively extending their reach and utility. With integrations, your Spokes can seamlessly work within your favorite messaging platforms, customer support tools, social media channels, and more!

#### Included Integrations

SpokesAI comes with several pre-built integrations that you can enable for your Spokes:

-   **iFrame**: Allows your Spoke to function within a web page or application. This integration is ideal for incorporating your Spoke into your website for customer support, live chat...
-   **Telegram**: Connects your Spoke to the Telegram messaging app. Your Spoke can now be a Telegram bot, capable of interacting with users on the platform.
-   **Slack**: Links your Spoke to your Slack workspace. You can use your Spoke as a smart Slack bot in each channel, providing assistance, updates, and more to your team.

[TO DO: Add detailed instructions or link to guides for setting up each integration]

#### Build Your Own

What if you want to use a Spoke with a platform that isn't yet supported by SpokesAI's included integrations? That's where the SpokesAI API comes in! The API allows you to build custom integrations, connecting your Spokes to virtually any platform or service.

The process of building your own integration involves using the SpokesAI API to send user inputs to your Spoke and retrieve its responses. These can then be displayed on the platform of your choice.

For more detailed instructions, check out the SpokesAI API Documentation. Building your own integration requires some technical know-how, but it opens up endless possibilities for using your Spokes!

Remember, integrations can greatly enhance your Spoke's capabilities and reach. Whether you're using included integrations or building your own, ensure to design and use them responsibly to create positive user experiences.

## APP Guide

The app comprises five primary sections: Home, Spokes, Bibliothecas, Integrations and Config. Each section is designed to facilitate the management of your SpokesAI environment.

1. **Home**: Your starting point in the SpokesAI universe. This dashboard hosts the 'Posts' section which stars news on app changes, tutorials, and other relevant content. Keep an eye on this page for updates, news, and tips on using SpokesAI. Here, you can also find links to the App's pages.
    
2. **Spokes**: This is where your AI team comes to life. The Spokes page allows you to manage your individual Spokes. You can create, delete, and edit Spokes. Here, you'll also find templates, pre-configured Spokes ready to be tailored to your specific needs. Use these templates as a base to fast-track your Spoke creation process. Also, the option to generate an iframe for each Spoke is available, giving you the ability to embed your Spoke into any web page.
    
3. **Bibliothecas**: The Bibliothecas page is the knowledge repository for your Spokes. Here, you can create, edit, and delete bibliothecas. Think of it as the library where your Spokes go to study!

4. **Integrations**: From this page, you may manage your integrations, letting your spokes go out to play into different platforms - such as Slack or Telegram.

5. **Config**: Last but not least, the Config page holds your user account details. Here, you can find your API key, the total number of conversations your Spokes have held, and the total number of Spokes you have created. Here is also shown your subscription usage and a list of the still open conversations you own, to continue or finish them.
    
Navigating these five pages will give you full control over your Spokes and the environment they operate in. 

```
NOTE: If you want to change language or log out, use the "user" icon in the top right corner. 
```

## Further Info

Please note that this guide is a general overview. For more detailed technical information, developers can refer to the [Technical Documentation](#). For any additional questions, visit our [FAQ](FAQ.md) section, talk with our support agents in-app or [contact our support team](#).

## Troubleshooting

If you have any problem using SpokesAI app, you can talk with our support agents in-app or [contact our support team](#).


