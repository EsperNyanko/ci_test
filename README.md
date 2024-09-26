# Introduction
To try a Hello World-style CI (Continuous Integration) example on GitHub, using GitHub Actions is the simplest option. GitHub Actions is a CI/CD service provided by GitHub that allows you to automatically run tests, builds, deployments, and more whenever an event occurs in your repository.

# Coding Rules
1. Do not hard-code context into shell commands; instead, pass it through environment variables.
2. Enclose all environment variables in double quotes.

# Variables
If you want to use the same environment variables across multiple workflows, use Variables.

To use Variables, prior registration is required. From the repository page, click the ① Settings tab. Next, select ② Secrets and variables followed by ③ Actions from the left menu. Then, open the ④ Variables tab and click ⑤ New repository variable.

