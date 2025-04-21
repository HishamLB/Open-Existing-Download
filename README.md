# Open-Existing-Download
This is an extension for firefox (tested on Floorp only) that first checks if the file you're about to download already exists in your download folder, if it does it will open that file instead of downloading the file again. 

Installation:
Go to your add-ons tab, press the cog and select "Install add-on from file" and select the .xpi file.

You need to change some settings to allow extensions to open a file:/// tab. [Do note that this is generally not recommended so proceed with caution]
1. Go to your about:config and set capability.policy.localfilelinks.sites = "moz-extension://YOUR-EXTENSION-ID" (you can find the extension-id after you've added the extension)
2. security.fileuri.strict_origin_policy = false
