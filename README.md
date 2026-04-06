# Simple Credits Generator for Unity
A very simple credits generator for Unity that uses ```.CVC``` files to create a horizontal layout of credits.

Comes with prefabs if you'd like to add any extra customisation!
Simply add the Generator to a Canvas and provide it the 'UI_CreditSection' Prefab.

**The credits UI layout is organised as follows:**
- Credits Layout (Root)
  - Scroll Viewport
    - Content:
      - Credit Section (UI_CreditSection)
        - title of credit
        - Names:
          - ...

### Credit Section Prefab:
Organise how you want each section to look here.

<img width="924" height="309" alt="UI_CreditSection-Prefab" src="https://github.com/user-attachments/assets/4096ef95-9dcd-4c90-97a7-72c07b0a2ae9" />

### Credit Prefab:
Put the name of the person here.

<img width="512" height="223" alt="UI_Credit-Prefab" src="https://github.com/user-attachments/assets/41e36e4d-49ea-41e4-bad8-e7e846fe6dad" />

### Asset Creator Window:
The tool uses an window for you to select your file and output:

<img width="691" height="400" alt="Credits Importer Window" src="https://github.com/user-attachments/assets/d69702c3-b6d1-41eb-bc9f-8091bb1a1836" />

**The tool requires you to ustilise a specific template that formats the credits as:**

| Name | Credit/Role |

Here's the template I recommend using, which you can download on Google Drive Here:
https://docs.google.com/spreadsheets/d/1ie20IqC23GBsTRs3vIIlmATrsaPglf3C_jttVqN_91U/edit?usp=sharing

### Updating the UI:
Once the scriptable object asset has been provided, you can either just start the game, or use the drop-down menu on the script to create it manually:

<img width="399" height="439" alt="Credits_Importer-Dropdown_Menu" src="https://github.com/user-attachments/assets/8d33975b-5054-40f2-b9bc-9cebde8c10b6" />


## Video Demonstration:
https://github.com/user-attachments/assets/1c2b8c88-6138-4019-a7f3-9c9d786dc949
