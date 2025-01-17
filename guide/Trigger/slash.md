# Slash Command

# Basic Information
This trigger type, will trigger when a user uses a slash command. This needs to be a slash command from the bot!

# Creating a slash command
Go to the slash command build page and create a new slash command!
![](https://i.ibb.co/6NPBrfX/image.png)
![](https://i.ibb.co/9tCFrTS/image.png)

# Slash Command Builder
Every slash command needs a name, a description. 

Slash command options are like argument in message command.

## Slash Command options
In Option List you can add a new option by selecting its type.

Every option has a name, a description and a type.
You can set it,if the option is required or optional.
#### Option type
Option validates that you can only select the correct type.
* STRING 
* INTEGER
* BOOLEAN
* MENTION
* ROLE
* CHANNEL
* USER

Example Type USER:
User can only provide a user .It is not possible to provide text or invalid input.

## Option Choices
String and Number type supports choices.If you provide choices,the user can only select those and can't provide any custom text/number.


## Creating a Custom Command 
Go to the custom command build page and create a new custom command!
Then navigate to the custom command editor by clicking on the edit button.
Change the triggertype to `slash_command` and fill in the trigger field with the name of the command.

###  Retriving Options
You can retrieve the options by using the following function [$getCommandOption](../Message/getCommandOption.md)
