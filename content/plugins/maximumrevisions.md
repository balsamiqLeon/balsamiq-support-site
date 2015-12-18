---
date: 2015-05-09T16:46:35+02:00
title: "“Maximum Number of Pinned Revisions Exceeded” Error in Mockups 3 for Google Drive"
menu:
  menuplugins:
    parent: plugins
weight: 140
---

Are you getting the following error message when trying to save your file in Mockups 3 for Google Drive?

![](https://media.balsamiq.com/img/support/prodfaqs/revisions.png)

## Why am I getting this?

When using the Balsamiq Mockups plugin, all the changes are always autosaved in Google Drive and a new 'not' pinned revision is created every time you close the app. On the other hand, using the command "Save" will instead create a "pinned" revision on Drive.

Seeing this error message means that you've reached the maximum number of pinned versions allowed for your account.

Google Drive automatically purges (or "prunes") revisions in order to optimize disk usage. To prevent this from happening, you can manually "pin" revision(s) that you don't want Drive to purge and also unpin or delete the one(s) you don't need.

## How do I get rid of the error?

To resolve the error message, you will need to either unpin or delete a pinned version. First you will need to right-click on the related BMPR file and select "Manage versions".

![](https://media.balsamiq.com/img/support/prodfaqs/manageversions1.png)


Then once you've identified a pinned version (little tick box on the left side of "Keep forever"), you can either unpin or delete it using the contextual menu, as shown above:

![](https://media.balsamiq.com/img/support/prodfaqs/manageversions2.png)

In general, a good practice is to 'trust' the auto-saving functionality of the app and use the "Save" command only to pin important revisions that you want to keep in the future (i.e. the ones that you do not want Drive to purge).

Hope this helps! Please [contact us](https://balsamiq.com/company/contact/) if you need any further assistance with this.