# PR Templates
## What is a Pull Request (PR) Template?
Creating a Pull Request (PR) using a PR Template in GitHub helps standardize the information developers include when contributing code. This ensures consistency, clarity, and easier code reviews.

A PR template is a pre-filled form that appears every time someone opens a pull request in the repository. It helps contributors provide:
    - Purpose of the PR

    - Changes made

    - Checklist for readiness

    - Related issues, screenshots, etc.

## How to create a PR Template in GitHub
 Step 1: Create a .github Folder
 In the root of your repo, create a folder named:

 `.github/`

 Step 2: Add the PR Template File
 Inside the .github/ folder, create a file named:

 `PULL_REQUEST_TEMPLATE.md`
 You can also place it in .github/PULL_REQUEST_TEMPLATE/ if you want multiple templates (for advanced use).

 Step 3: Write the Template
 Example PULL_REQUEST_TEMPLATE.md:
 <pre> Descrption <br> ## 📝 Description

Please include a summary of the change and which issue is fixed.

Fixes # (issue)

## ✅ Type of Change

- [ ] Bug fix 🐛
- [ ] New feature ✨
- [ ] Breaking change ❗
- [ ] Documentation update 📚

## 📸 Screenshots (if applicable)

_Add screenshots here._

## 📋 Checklist

- [ ] I have tested my code
- [ ] I have updated documentation if needed
- [ ] My changes follow the repository’s code style
</pre>

Step 4: Open a Pull Request
When a contributor opens a PR:

    - GitHub auto-fills the description field with your template content.

    - They just edit it with their details.