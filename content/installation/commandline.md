---
title: Can I Install Mockups from the Command Line?
date: '2015-05-09T14:46:35.000+00:00'
weight: 210
menu: "menuinstallation"
product: "Installation FAQs"
draft: ''
---
Mockups 3 for Desktop can be registered and unregistered via the command line with the following commands:

## Installing and Uninstalling

To install Mockups 3 for Desktop to the Program Files directory, use the following command. You can change the target directory to the folder of your choosing by replacing "C:\Program Files (x86)" with your chosen directory.

{{% alert info %}}**Note:** The installation filename changes based on the version of Mockups it is installing. Be sure to use the correct file name when running the following command.{{% /alert %}}

`[CurrentMockupsVersion].exe /VERYSILENT /DIR="C:\Program files (x86)"`

To uninstall Mockups 3 for Desktop, enter the following commands into an elevated Command Prompt.

`wmic
product where name="Balsamiq Mockups 3" call uninstall /nointeractive`

* * *

## Registering and Unregistering

Before registering Mockups 3 for Desktop, you will have to locate your registration email. The License Name and License Key can be found there.

To register Mockups 3 for Desktop, use the following command.

`"C:\Program Files (x86)\Balsamiq Mockups 3\Balsamiq Mockups 3.exe" register LICENSENAME LICENSEKEY`

If your license name has a space in it, you will need to wrap the name in quotes.

To unregister Mockups 3 for Desktop, use the following command.

`"C:\Program Files (x86)\Balsamiq Mockups 3\Balsamiq Mockups 3.exe" unregister`

* * *

## Additional Resources

Looking for information on how to perform a silent installation of Mockups for Desktop on many end-user machines? [Here you go](/installation/silentinstall/).
