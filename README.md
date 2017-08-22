# Zapier for Alfred

[![](https://cdn.zapier.com/storage/photos/3ccde4f9fed3efeea6605d44dbcaff3a.png)](https://zapier.com/blog/zapier-for-alfred/)

Trigger your [Zapier](https://zapier.com/) workflows from Mac productivity app [Alfred](https://www.alfredapp.com/).

Zapier is a web app automation tool that lets you build workflows with over 750 popular web apps—from Salesforce to Gmail, Stripe to Evernote—to automate your tasks and get more done, with search actions to find data in your apps, actions to add data to your tasks and get work done automatically, and multiple steps to get a whole workflow of tasks done at once. And with Alfred, you can trigger those Zap workflows right from your Mac keyboard.

You can use this workflow to trigger any Zap that starts with a Webhooks trigger, via its bash CURL command. [Download Zapier for Alfred](https://github.com/zapier/Zapier-for-Alfred/archive/master.zip), and install it in Alfred—then here's how to use it:

1. Make a Zap, if you don't already have it. Open [zapier.com](https://zapier.com/), login to your Zapier account, and make a new Zap with the Webhooks Catch Hook trigger.
2. Copy the Webhooks URL from Zapier. It'll be something like https://hooks.zapier.com/hooks/catch/123456/1abcde/.
3. Double-click the Value field beside ZAP_URL on the right pane of the workflow settings in Alfred, then paste your Webhooks URL instead of the instruction text and press save.
4. Open Alfred, type Zap followed by the text you want to use, then press enter.
5. Now go back to Zapier and finish setting up your Zap.
6. Whenever you want to run that Zap, just open Alfred, type Zap, and enter the text you want to send to Zapier.

Want to use this workflow with more than one Zap? Just right-click on "Zapier for Alfred" in the sidebar, select Duplicate, then add your new Zap's URL to the environment variable on the right—and add a new keyword to the keyword option.

Enjoy!

_For more info, see our full tutorial on [How to Use Zapier with Alfred](https://zapier.com/blog/zapier-for-alfred/)._