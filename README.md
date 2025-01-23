# Sysmac Studio Function Block Library

This repository contains a collection of well-structured and reusable Function Blocks (FB) for use in **Sysmac Studio**. The primary goal of this library is to enable programming that closely resembles **object-oriented programming (OOP)**, ensuring modularity, reusability, and maintainability in automation projects.

With over 15 years of experience working with Omron PLCs, this library has been developed from a rich base of over 200 Function Blocks. The goal of this project is to revisit and modernize all objects, leveraging the latest techniques and aligning them with current standards and best practices.

## About This Project
- **Experience**: Developed based on extensive experience in industrial automation with Omron PLCs.
- **Size**: Contains over 200 Function Blocks, structured and refined for modular use.
- **Goal**: Modernize and adapt existing objects using up-to-date techniques and normalization standards.
- **Collaboration**: Users are encouraged to request which components should be prioritized for adaptation to meet their specific needs.

For detailed usage and guidelines, refer to the [Wiki](https://github.com/Folders/Omron_Library_FB/wiki) where you can find comprehensive documentation, examples, and best practices for integrating this library into your projects.

Feel free to contribute, ask questions, or suggest improvements to make this library even more valuable for the community.


# Using the Project

This project is designed to integrate seamlessly with the **Git Extension** for Sysmac Studio (Version Control Explorer). If you are not using this extension, follow the steps below to manually import the project into Sysmac Studio.

## Steps to Use the Project Without Git Extension

### Step 1: Download the Project
Download the project from the GitHub repository as a ZIP file.

### Step 2: Extract the Project
Extract the ZIP file and locate the folder named `Project`. Place this folder in the following directory on your system:
```C:\OMRON\Data\Solution```

### Step 3: Rename the Project Folder
The folder must be renamed with a unique **GUID** to be recognized by Sysmac Studio. This GUID can be found in the name of the `manifest` file within the `Project` folder. For example, as shown in the image:

- Manifest file: `926ff688-62b0-4319-b4dc-53e6f7fe298b.manifest`
- Rename the folder to: `926ff688-62b0-4319-b4dc-53e6f7fe298b`

![Example of manifest file and GUID](https://github.com/Folders/Omron_Library_FB/blob/master/Documents/images/readMe/GUID.png)

### Step 4: Open the Project in Sysmac Studio
Once the folder is renamed, it will appear in the **Open Project** menu of Sysmac Studio. Open Sysmac Studio, navigate to **Open Project**, and you should see the project listed with the "Last Modified" date as `01.01.0001`.

![Opening the project in Sysmac Studio](https://github.com/Folders/Omron_Library_FB/blob/master/Documents/images/readMe/OpenProject.png)

By following these steps, you can use the project even without the Git extension. If you encounter issues or need assistance, feel free to reach out for support.
