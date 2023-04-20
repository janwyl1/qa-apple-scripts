# QA Apple Scripts

Series of Apple Scripts to speed up QA testing

# Installation Instructions
- Download the scripts
- Double click to open them in Script Editor and choose Export -> Application
- Run them manually once and accept security warning
- Set up a quick action to run the script using Automator. See: https://www.addictivetips.com/mac-os/run-an-applescript-with-a-keyboard-shortcut-on-macos/
- Assign them to a keyboard shortcut via System Preferences -> Keyboard -> Shortcuts -> Services. See: https://apple.stackexchange.com/questions/175215/how-do-i-assign-a-keyboard-shortcut-to-an-applescript-i-wrote
- Add automator to Settings -> Security & Privacy -> Accessbility


Works with Chrome

## jiraCommentAutofill / jiraCommentAutoFill Steps
Adds a basic test case template to the description or comment field of a Jira ticket

## jiraTicketTemplate
Copies a basic test case template to the clipboard (on older versions of Jira, writing to the description field using innerHtml wouldn't work so it required an extra manual paste step)

## jiraCommentMergedIntoMaster
Adds a 'Merged into master' comment to a Jira ticket 

## sageCardNumber
Copies a sage test credit card number to the clipboard
