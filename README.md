# Automation Lab  

> Please note that this project is ongoing and is meant solely for learning purposes. Your feedback would be greatly appreciated, as I am using this opportunity to learn.  

## Objective  

To create a dedicated environment for testing and developing automation solutions in cybersecurity, system administration, and security operations. This lab focuses on hands-on experience with scripting, task automation, and orchestration using tools such as Python, PowerShell, and automation frameworks.  

## Initial Setup  

***1. Installing hypervisor***  

- You can use VMware Workstation or VirtualBox, based on your preference. More details [here](https://github.com/mmhgwyjs/homelab?tab=readme-ov-file#hypervisor).  

***2. Setting Up a Base Machine***  

- A Windows and/or Linux machine will be configured for running automation scripts and tools. Follow the steps outlined here: [Windows Lab Setup Guide](https://github.com/mmhgwyjs/windows-lab?tab=readme-ov-file#initial-setup) or [Linux Lab Setup Guide](https://github.com/mmhgwyjs/linux-lab?tab=readme-ov-file#initial-setup).  

***3. Installing an IDE in Windows***

To facilitate development, we will install **Visual Studio Code (VS Code)**:  

- Download VS Code from the official website: [Download VS Code](https://code.visualstudio.com/Download)

  ![VS Code Download](https://github.com/user-attachments/assets/35e2f7c7-647f-4428-b6ed-c097f621c6bd)  

- Choose the appropriate version based on your operating system.  
- Proceed with the installation:

  ![VS Code Installation](https://github.com/user-attachments/assets/025d05dd-c03d-4273-9fc0-cb6dc4570426)

  ![VS Code Setup](https://github.com/user-attachments/assets/f332ccfe-7963-4487-bc48-0484b20c4a2d)  

- Installation complete!

  ![Installation Complete](https://github.com/user-attachments/assets/e86b515a-ce39-4ee1-aa3f-713ffa8ab591)  

***4. Installing Python 3***

Python will be used as the primary scripting language for automation.  

- Download Python from the official website: [Download Python](https://www.python.org/downloads/)

  ![Python Download](https://github.com/user-attachments/assets/88d9d6aa-6581-4261-9b5b-e4a3af162792)

- Run the downloaded package and follow the straightforward installation process.  

***5. Installing Python Extension in Visual Studio Code***

To enhance Python development in VS Code:  

- Open **VS Code**, go to the **Extensions** tab, and search for "Python".  

- Click **Install** on the official Microsoft Python extension.

  ![VS Code Extensions](https://github.com/user-attachments/assets/ab0457fd-45ac-4d04-aa8c-600a495b0714)

  ![Install Python Extension](https://github.com/user-attachments/assets/fd1633d8-4394-4108-aff2-76ba180c4343)  

***6. Creating a Project Folder***

To organize our automation scripts, we need to create a dedicated project folder.  

- Create a new folder and set it as the project directory.  
- Navigate to the created folder and run the following command to open it in VS Code:  

   ```sh
   code .
   ```

  ![Open VS Code](https://github.com/user-attachments/assets/ed037f67-899f-4d3c-983b-17502d5e752f)  

- When prompted, select **"Trust the Authors"** to ensure full functionality.

  ![Trust the Authors](https://github.com/user-attachments/assets/702c0e98-fd9e-4bc2-b8af-e84e7f9631ac)  

***7. Setting Up a Virtual Environment***  

#### Why Use a Virtual Environment?  

A virtual environment (venv) isolates dependencies for your project, preventing conflicts with system-wide Python packages. This ensures a clean and reproducible development environment.  

- While in VS Code, press **CTRL + SHIFT + P** to open the command palette.  
- Search for **"Python: Create Environment"** and select it.

  ![Python: Create Environment](https://github.com/user-attachments/assets/bed64580-5c59-4a74-b3fd-d6eeb7621c5d)

- Choose **venv** as the environment type.

  ![Select venv](https://github.com/user-attachments/assets/d30fddd3-b12c-48af-93b3-47059695544a)

- Select **Global Interpreter Path** to use the default Python installation.

  ![Select Global Interpreter](https://github.com/user-attachments/assets/a9081b9b-e864-4932-94a1-03a5c7907124)  

- Once created, the virtual environment should appear in the **Explorer Pane** on the left side of VS Code.

  ![Virtual Environment Setup](https://github.com/user-attachments/assets/e4641771-134a-4504-b5a0-fcd3c3862edb)  

- At this point, we are ready to create our first automation script!

---

### We've successfully set up the automation lab with all the essential tools. Now, it's time to put our knowledge into action. Let's dive into the practical exercises below and start automating!

---

## Lab Exercises  

| Exercise        | Description                        | Link               | Status       |
|----------------|------------------------------------|--------------------|--------------|
| Sample Project | Automate a basic task | [View Exercise]() | In Progress |
