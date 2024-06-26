# An example guide to NSSP Sample Reports

Hello everyone and thank you for your interest in the presentation.

WIP: There are a few items I want to expand upon, including:
1. Updating the readme. (Done)
2. Add sections for the first half of the paired R markdown script. (Done)
3. Re-format the python script section headers to be in parity with the R markdown script.
4. Add a section to the readme on building queries in ESSENCE and then moving them to a script (e.g. R or python).
5. Add sections for the latter half of the script that includes graphical generation and outputting to a docx document.
6. Transitioning to other potential uses of retrieving NSSP data/summaries through ESSENCE.


# An overview of the keyring concept

For many operations, Windows will store credentials in a user directory. This can help a user access and maintain their logins.

The easiest way to find where windows credentials are stored is through the search bar, as shown below.

![Image showing the Windows Search feature being used to find the Manage Windows Credentials tool.](https://github.com/micastro-ruhs/NSSP_Sample_Report/blob/main/img/Keyring_01.png)

You can see, shown below, a few items in the Generic Credentials section. Some of them are credentials handled by the Office365 environment; but you also have the option to 'Add a generic credential'. This would be the manual way to create or update a credential.

![Image overviewing the Credential Manager, along with a red circle around the item where the login to NSSP and ESSENCE are stored. I name it 'NSSP ESSENCE'.](https://github.com/micastro-ruhs/NSSP_Sample_Report/blob/main/img/Keyring_02.png)

Since NSSP requires a password change every 90 days, you will need to be acquianted with making those updates in various places. This is one easy way to manage the storage of a credential outside of a shared network drive, and outside of storing a password in the script.

![Image showing that you can manually enter or update the username or password through Credential Manager.](https://github.com/micastro-ruhs/NSSP_Sample_Report/blob/main/img/Keyring_03.png)


# (WIP) ESSENCE Queries and Transition to a Script

