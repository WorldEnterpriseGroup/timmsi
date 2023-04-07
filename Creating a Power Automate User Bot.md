## What is a Power Automate User Bot:

* A Power Automate user bot is an automated workflow that can be created using the Power Automate platform (formerly known as Microsoft Flow).

* The purpose of a user bot is to automate certain tasks within a given software or application, such as sending automated responses to incoming messages or 
  processing data from one system and passing it on to another.

* In the case of a Power Automate user bot for Microsoft Teams, it can be used to automatically respond to messages received in a group chat, providing quick
  and helpful responses to users even when the team member is not available.

* By automating routine tasks, user bots can save time and increase efficiency for teams, allowing team members to focus on more complex tasks that require their
  attention.
  
## Creating a Power Automate User Bot for Automated Messaging in Microsoft Teams:
  
* Here are the step-by-step instructions:

### Sign in to Power Automate:

* Visit the Power Automate website and sign in by clicking on the "Sign in" button at the top right of the screen.

### Create a new Automated Cloud Flow:

* Once you're signed in, click on the "Create" button on the left-hand side of the screen and select "Automated Cloud Flow."

### Name your flow and select triggers:

* Name your flow something memorable, like "Auto Fajar." In the triggers section, click on "When a new message is added to a group chat," and select the group
  chat you want to monitor. You can select multiple group chats if you wish.

### Add an action:

* Click on "New Step," and in the search bar, type "Teams." From the dropdown, select "Microsoft Teams," and then select "Get message details."

### Get Conversation ID:

* Click on the "Message ID" dropdown, and select "Conversation ID." This will allow your bot to identify the group chat.

### Add another action:

* Click on "Add an action" and search for "Microsoft Teams" again. Select "Get an @ mention token for a user" and input your user ID.

### Add final action:

* Now, click on "Add an action" and search for "Microsoft Teams" one more time. Select "Post a message in a channel or chat." In the "To" field, select "Group
 Chat," and input the conversation ID you got in Step 5.
 
* In the "Message" field, type "Hello! I will get back to you soon." In the "User Display Name" field, enter your name.

### Add a delay:

* Add a delay by clicking on the "+" button and selecting "Delay." In the "Count" section, input the number of seconds you want your bot to wait before
  replying.
* For example, you could input 15,20, or 37 seconds.

### Save your flow:

* Once you're done, click on "Save" to save your flow.

Congratulations! You've successfully created your own Power Automate User bot that can talk on your behalf when you're not available.




