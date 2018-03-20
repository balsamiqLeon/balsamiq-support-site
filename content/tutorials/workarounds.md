---
title: Common Workarounds
date: '2015-12-16T11:00:00.000+00:00'
weight: 330
menu: "menututorials"
draft: ''
product: "Tutorials & Videos"
---
Balsamiq should allow you to achieve most of your needs as it is designed (assuming it is [the right tool for you](/sales/howtochoose/)). However, some features can be harder than others to implement and sometimes using a workaround is the best way to address an immediate need. We decided to collect those workarounds, and make them available for you here.

Most of these tips and tricks are based on customer requests or questions so, once again, **thank you friends**! If you have any other requests or workarounds you'd like to share, please [reach out](https://balsamiq.com/company/contact/#/t) and tell us all about it. :)

We will keep this page updated with common workarounds as we uncover them. And we are always happy to discuss any [feature requests](https://forums.balsamiq.com/) you may have.


---

## Make Any Control Linkable

Sometimes you want to create a [link](https://docs.balsamiq.com/desktop/linking/) from a control that doesn’t natively support it. Here's a quick way to do it:

1. Add a **Rectangle** control
2. Make it borderless and transparent
4. Move and resize the rectangle to overlay your other control (Calendar in this case)
5. Set up your link
6. Group the controls together

![](//media.balsamiq.com/img/support/tutorials/workarounds/linkable-area.png)

---

## Link to Alternates

Here is a quick way to [link](https://docs.balsamiq.com/desktop/linking/) to an [alternate version](https://docs.balsamiq.com/desktop/alternates/) when needed: putting the focus on an alternate version in the editor will result in links pointing to it (instead of the official wireframe), even when using the [Full Screen Presentation mode](https://docs.balsamiq.com/desktop/fullscreen/).

![gif](//media.balsamiq.com/img/support/tutorials/workarounds/alternate-focus.png)

{{% alert info %}}**Note:** For PDF exports, include only the alternate you want to link to, and exclude the official version, will make the link pointing to the first alternate for that specific wireframe in the PDF. More details on exporting a specific set of wireframes [here](https://docs.balsamiq.com/desktop/exporting/#exporting-to-pdf).{{% /alert %}}

---

## Indent inside Any Control

Need to indent items in controls that don't support it, like the Checkbox group or Radio Button Group?

1. Duplicate your control
2. Remove lines that need to be indented from the first one
3. Remove all lines expect indented ones from the second one
4. Overlay second control on the first one
5. Group the controls together

![gif](//media.balsamiq.com/img/support/tutorials/workarounds/indenting.png)

You can even transform the group to a [symbol](https://docs.balsamiq.com/desktop/symbols/#creating-symbols). This will make it easier to use from the [UI library](https://docs.balsamiq.com/desktop/overview/#the-ui-library) or [Quick Add](https://docs.balsamiq.com/desktop/overview/#the-quick-add-tool).

---

## Add a Background Color to Any Control

Not all controls have a background color property so here is a quick way to add it to any control (or part of control):

1. Add a **Rectangle** control and make it borderless
2. Set the background color to the desired one
3. Set its opacity to 25%
4. Move and resize the rectangle to overlay your other control (Data Grid in this case)
5. Group the controls together

![](//media.balsamiq.com/img/support/tutorials/workarounds/background-color.png)

You can also set up a **border color** the same way if needed.

{{% alert info %}}**Note:** This trick can also be used to specify multiple selection, see the details [here](../multipleselection/).{{% /alert %}}

---

## Add a Disable State to Any Control

Here is a quick way to make any part of a control disabled:

1. Add a **Rectangle** control and make it borderless
2. Set its opacity to 75%
4. Move and resize the rectangle to overlay your other control (Tabs Bar in this case)
5. Group the controls together

![](//media.balsamiq.com/img/support/tutorials/workarounds/disable.png)

---

## Add a Blank Row to a ComboBox or Menu Control

Adding a blank row can be tricky in those controls because leaving a blank line of text will trigger a separator line. Here's a quick workaround: you can use **{color:fff}Blank{color}** for your blank row (more text macros [here](https://docs.balsamiq.com/desktop/text/#basic-formatting)).

![gif](//media.balsamiq.com/img/support/tutorials/workarounds/blank-row.png)

---

Again, if you have a workaround you'd like to share, please [reach out](https://balsamiq.com/company/contact/#/t) and tell us!
