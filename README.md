# Zapier for Alfred

Trigger your [Zapier](https://zapier.com/) workflows from Mac productivity app [Alfred](https://www.alfredapp.com/).

You can use this workflow to trigger any Zap that starts with a Webhooks trigger, via its bash CURL command. Install the Alfred workflow—then here's how to use it:

1. Make a Zap, if you don't already have it. Open [zapier.com](https://zapier.com/), login to your Zapier account, and make a new Zap with the Webhooks Catch Hook trigger.
2. Copy the Webhooks URL from Zapier. It'll be something like `https://hooks.zapier.com/hooks/catch/123456/1abcde/`.
3. Double-click the /bin/bash Run Script item on the right of this Afred workflow.
4. Replace the `ZAP_URL` text with the URL you just copied, leaving the `?text={query}` text at the end.

That should leave you with a script that looks like:

`curl https://hooks.zapier.com/hooks/catch/123456/1abcde/?note={query}`

5. Save that, then open Alfred, type `Zap` followed by the text you want to use, then press enter. 
6. Now go back to Zapier and finish setting up your Zap.
7. Whenever you want to run that Zap, just open Alfred, type Zap, and enter the text you want to send to Zapier.

Want to use this workflow with more than one Zap? Just right-click on "Zapier for Alfred" in the Alfred sidebar, select _Duplicate_, then add your new Zap's URL to the Bash script in that copy of the Zapier for Alfred workflow—and add a new keyword to the keyword option.

Enjoy!

_For more info, see our full tutorial on [How to Use Zapier with Alfred](https://zapier.com/blog/zapier-for-alfred/)._