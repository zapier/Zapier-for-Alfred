# Zapier for Alfred

[![](https://cdn.zappy.app/a918d91296c7bdd21e9519a909266d73.png)](https://zapier.com/blog/zapier-for-alfred/)

Trigger your [Zapier](https://zapier.com/) workflows from Mac productivity app [Alfred](https://www.alfredapp.com/).

Zapier is a web app automation tool that lets you build workflows with over 5000 popular web apps — from Salesforce to Gmail, Stripe to Evernote — to automate your tasks and get more done, with search actions to find data in your apps, actions to add data to your tasks and get work done automatically, and multiple steps to get a whole workflow of tasks done at once. And with Alfred, you can trigger those Zap workflows right from your Mac keyboard.

You can use this workflow to trigger any Zap that starts with a Webhooks trigger, via its bash CURL command. [Download Zapier for Alfred](https://github.com/zapier/Zapier-for-Alfred/archive/master.zip), and install it in Alfred. Here's how to use it:

1. Make a Zap, if you don't already have one. Open [zapier.com](https://zapier.com/), log in to your Zapier account, and make a new Zap with the Webhooks by Zapier app, using the Catch Hook trigger.
2. Copy the Webhooks URL from your Zap. It'll look something like `https://hooks.zapier.com/hooks/catch/123456/1abcde/`.
3. Double-click the Value field beside ZAP_URL in the Environment Variables tab in the workflow settings in Alfred (click the {x}), then paste your Webhooks URL and click save.
4. Open Alfred, type `zap` followed by the text you want to send, then press enter.
5. Go back to Zapier and finish setting up your Zap.
6. Whenever you want to run that Zap, just open Alfred, type `zap`, and enter the text you want to send to Zapier.

If you run into any trouble with the information coming through the Zap, please make sure that you are not escaping Spaces and Brackets:

![Escaping](https://cdn.zappy.app/f7302b7883401e2ad78e5e2d850fe7ca.png)

These settings can be found by clicking Configure Object in the Run Script object.

Want to use this workflow with more than one Zap? Just right-click on "Zapier for Alfred" in the sidebar, select Duplicate, then add your new Zap's Webhook URL to the environment variables and add a new keyword to the keyword option.

Enjoy!

_For more info, see our full tutorial for [How to Use Zapier with Alfred](https://zapier.com/blog/zapier-for-alfred/)._
