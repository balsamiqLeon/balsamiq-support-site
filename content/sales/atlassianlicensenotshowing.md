---
title: Balsamiq for Confluence Server or Jira Server Says It's Unlicensed, but It Is!
date: '2015-05-09T14:46:35.000+00:00'
weight: 80
menu:
  menusales:
    weight: 80
draft: ''

---

If you bought a license of Balsamiq for Confluence Server or Balsamiq for Jira Server from Balsamiq, installed it, and your instance is still showing the plugin as "Unlicensed" or "Free Trial", this article is for you.

First of all, your plugin is working correctly, you did everything right.

We offer what Atlassian calls "dual licensing" for our server plugins, meaning that you can purchase them either from Atlassian via the Atlassian Marketplace or directly from Balsamiq. The pros and cons of each option are described [here](/sales/marketplace/).

The problem you are seeing is because the Universal Plugin Manager (what you're using when you go to "Manage Add-Ons" on your Confluence or Jira installation) ONLY understands Marketplace-issued licenses. It doesn't recognize that the plugin is indeed licensed via the Balsamiq-issued key, so it just treats it as a free trial. You can safely ignore those messages and continue working. If you want to verify the real status of your plugin, go to the Configure link. You'll find lots of accurate info there. :)

![](//media.balsamiq.com/img/support/docs/confluence/unlicensed/upmlies.png)
