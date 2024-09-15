# 🚀 **VCS Setup Guide: Bitbucket, GitHub, and GitLab**

This guide walks you through setting up repositories on **Bitbucket**, **GitHub**, and **GitLab**—the most popular Git-based Version Control Systems. Whether you're managing code, collaborating with a team, or deploying applications, these platforms are essential tools for modern development workflows.

---

## 📑 **Table of Contents**
- [Introduction](#introduction)
- [Bitbucket Setup](#bitbucket-setup)
- [GitHub Setup](#github-setup)
- [GitLab Setup](#gitlab-setup)
- [Conclusion](#conclusion)
- [Contact Information](#contact-information)
- [References](#references)

---

## 🌟 **Introduction**

Version Control Systems (VCS) are key to modern software development. They allow teams to collaborate, track changes, and manage their codebases effectively. This guide provides simple, step-by-step instructions for setting up and using **Bitbucket**, **GitHub**, and **GitLab**.

---

## 🧰 **Bitbucket Setup** 

Bitbucket, by Atlassian, is ideal for teams using Jira and Trello. It offers seamless integration with these tools for project management and issue tracking.

### Steps to Set Up Bitbucket:
1. **Create an Account**: Go to [Bitbucket](https://bitbucket.org/) and sign up. 📝
   ![Bitbucket Sign Up](https://example.com/bitbucket-signup-image.png)

2. **Create a Repository**:  
   - Click **Repositories** → **Create Repository**.
   - Name your repository, choose public/private, and add a description if needed. 📁
   
   ![Create a Repository in Bitbucket](https://example.com/create-bitbucket-repo.png)

3. **Clone the Repository**:
   - Copy the clone URL and run the following Git command to clone the repo locally:
     ```bash
     git clone https://bitbucket.org/username/repository_name.git
     ```
     ![Clone Bitbucket Repository](https://example.com/clone-bitbucket-repo.png)

4. **Push Your Code**:
   - Add, commit, and push your changes using:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

5. **Collaborate**: Invite teammates by navigating to the repository settings and selecting **User and Group Access**. 👫

---

## 🐙 **GitHub Setup**

GitHub is the go-to platform for open-source development and collaboration, offering a vibrant community and extensive integrations.

### Steps to Set Up GitHub:
1. **Create an Account**: Head to [GitHub](https://github.com/) and sign up. ✍️
   ![GitHub Sign Up](https://example.com/github-signup-image.png)

2. **Create a New Repository**:  
   - Click **New** in the repositories section.
   - Fill in the repository name, set it as public/private, and optionally add a README. 📦
   
   ![Create GitHub Repository](https://example.com/create-github-repo.png)

3. **Clone the Repository**: 
   - Use the SSH or HTTPS link and clone it locally:
     ```bash
     git clone https://github.com/username/repository_name.git
     ```
     ![Clone GitHub Repository](https://example.com/clone-github-repo.png)

4. **Push Your Code**:
   - Use these Git commands to push your changes:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

5. **Collaborate**: Go to **Settings** → **Manage access** to add collaborators to the repository. 💻

---

## 🦊 **GitLab Setup**

GitLab offers a comprehensive DevOps platform that integrates Git repository management with CI/CD, security scanning, and monitoring tools.

### Steps to Set Up GitLab:
1. **Sign Up**: Visit [GitLab](https://gitlab.com/) and create an account. 📝
   ![GitLab Sign Up](https://example.com/gitlab-signup-image.png)

2. **Create a New Project**:
   - Click **Projects** → **New Project**.
   - Choose between a blank project, importing a repository, or using a template. 📁
   
   ![Create GitLab Project](https://example.com/create-gitlab-project.png)

3. **Clone the Repository**: 
   - Use the GitLab repository URL and clone the repo:
     ```bash
     git clone https://gitlab.com/username/repository_name.git
     ```
     ![Clone GitLab Repository](https://example.com/clone-gitlab-repo.png)

4. **Push Your Code**:
   - After making changes, push them to GitLab:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

5. **Collaborate**: Add members by navigating to the **Members** section under project settings. 🌐

---

## 📝 **Conclusion**

Setting up repositories on **Bitbucket**, **GitHub**, and **GitLab** is an easy and essential part of software development. Whether you're managing personal projects or collaborating with a team, each platform offers powerful tools to help streamline version control, automate workflows, and ensure smooth deployments. By following the steps above, you can quickly get started on any platform and take full advantage of Git's capabilities.

---

## 📧 **Contact Information**

If you have any questions or need assistance, feel free to reach out:

| Name         | Email Address                      |
|--------------|------------------------------------|
| Brij Singh   | brij.singh.snaatak@mygurukulam.co  |

---

## 📚 **References**

- [Bitbucket Documentation](https://support.atlassian.com/bitbucket-cloud/)
- [GitHub Documentation](https://docs.github.com/)
- [GitLab Documentation](https://docs.gitlab.com/)
- [Getting Started with Git](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
