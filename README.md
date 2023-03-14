# k3-fashion-labels-translation-tutorial

This repository contains all K3 Fashion's label files that are translated using the [Microsoft Translation Service](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/lifecycle-services/translation-service-overview), together with the [Custom-trained MT model](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/lifecycle-services/translation-service-overview#custom-trained-mt-model). It's designed to enhance the experience for partners and independent software vendors (ISVs) when they translate their solutions or add a new language for supported Dynamics products.

# Prerequisites

### 1) Multilingual App Toolkit Editor

Microsoft Translation Service uses a bilingual **XML Localization Interchange File Format (XLIFF)** file to store pairs of source languages and target languages. Because XLIFF is based on XML, you can open XLIFF files in any text editor. However, we recommend that you use XLIFF editors that are specifically designed to work with this format, the best approach would be the free [Multilingual App Toolkit Editor](https://learn.microsoft.com/en-us/windows/apps/design/globalizing/multilingual-app-toolkit-editor-downloads).

### 2) GitHub account

GitHub is an online platform for version control and collaboration that allows developers to host and review code, manage projects, and build software. It provides a web-based interface for Git, a popular version control system, allowing developers to track changes to their code and collaborate with others on the same project. GitHub offers features such as issue tracking, pull requests, code review, and project management tools, making it an essential tool for many software development teams. GitHub also provides a platform for open-source software development, allowing developers to share and contribute to open-source projects. It has become a key resource for developers and organizations around the world, with millions of users and thousands of projects hosted on the platform.

#### Creating a GitHub account

1. Go to the GitHub website (github.com) in your web browser.
1. Click the "Sign up" button in the upper right corner of the page.
1. Enter your desired username, email address, and password in the provided fields.
1. Choose the type of account you want to create (individual or organization) and provide any additional information as requested.
1. Complete the reCAPTCHA verification process to prove that you are not a robot.
1. Review the GitHub terms of service and click the "Create account" button to submit your information.
1. Once your account is created, you can customize your profile, set up repositories, and start collaborating with other developers on GitHub.

### Downloading GitHub Desktop

You can now use GitHub Desktop to clone repositories, create new repositories, commit changes, and manage your Git workflow.

1. Go to the GitHub Desktop website at desktop.github.com.
1. Click the "Download for [your operating system]" button.
1. After the download is complete, open the downloaded file to start the installation process.
1. Follow the instructions provided by the installer to install GitHub Desktop on your computer.
1. Once the installation is complete, open GitHub Desktop and sign in with your GitHub account.

# Repository folder and solution structure
<br/>

This repository contains a folder for each language, the following folders are available at the moment:

| Folder | Description |
| --- | --- |
| de | This folder contains the XLIFF file for the German language. |
| nl | This folder contains the XLIFF file for the Dutch language. |
| it | This folder contains the XLIFF file for the Italian language. |

# Getting started

## Asking to be a collaborator

A collaborator on GitHub is a user who has been given permission to contribute to a repository owned by another user or organization. Collaborators have access to the repository's code, issues, and pull requests, and they can make changes to the repository directly.

Repository owners can add collaborators to their repositories to allow them to contribute to the project. Collaborators can be added with different levels of access, ranging from read-only access to full administrative access. This allows repository owners to control who can make changes to their code and how much access each collaborator has to the repository.

Collaborators can be useful for working on open-source projects, sharing code with team members, or allowing others to contribute to your project. With GitHub's collaboration features, collaborators can work together to make changes to a codebase, track issues, and review pull requests, making it easier to work on complex projects with multiple contributors.

To ask to be a collaborator in our repository on GitHub, you can follow these steps:

1. Click on the "Issues" tab near the top of the repository's page.
1. Click the "New Issue" button.
1. In the "Title" field, type "Request to be added as a collaborator".
1. In the "Leave a comment" field, write a brief message explaining the name of the partner/customer, etc.
1. Click the "Submit new issue" button to create the issue.
1. Wait for the repository owner or an existing collaborator to review your request and respond to your issue.

Alternatively, you can directly reach out to us and ask to be added as a collaborator. You can do this by sending them a message on GitHub or by contacting us through other means of communication.

## Cloning the repository

Cloning a repository on GitHub means creating a local copy of a remote repository hosted on GitHub to your local machine. This allows you to work on the code and files in the repository locally and make changes without affecting the original repository on GitHub. Cloning a repository downloads the repository's code, files, and commit history to your local machine, which can be useful for contributing to open-source projects or collaborating with other developers.

When you clone a repository, Git creates a new directory on your local machine with a copy of the repository. This directory will contain all the files and folders in the repository, as well as the commit history and other Git metadata. You can use Git to make changes to the repository and push them back up to GitHub when you are ready to share your changes with others.

To clone our repository on GitHub, you can follow these steps:

1. Open GitHub Desktop on your computer.
1. Click on the "File" menu and select "Clone Repository".
1. In the "Clone a Repository" dialog box, select the "GitHub.com" tab.
1. Browse or search for the repository you want to clone.
1. Once you find the repository, click on it to select it.
1. Choose the local path where you want to clone the repository to your computer.
1. Click the "Clone" button to clone the repository.
1. Wait for the repository to download to your local machine. Once it is complete, you will have a local copy of the repository that you can work with.

Alternatively, you can also clone a repository on GitHub Desktop by following these steps:

1. Open the repository page on GitHub.com in your web browser.
1. Click on the green "Code" button and select "Open with GitHub Desktop".
1. GitHub Desktop will launch and ask you to choose the local path where you want to clone the repository.
1. Click the "Clone" button to clone the repository.
1. Wait for the repository to download to your local machine. Once it is complete, you will have a local copy of the repository that you can work with.

## Creating a pull request


                    
