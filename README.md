# github-user-access-checker
A Bash script that lists users who have read (pull) access to a given GitHub repository using the GitHub API. Built as part of my DevOps apprenticeship journey to gain hands-on experience with scripting, APIs, and automation.

---

##  Features

- Lists users with `read` (pull) access to any public/private GitHub repo
- Uses GitHub REST API with authentication
- Parses JSON output using `jq`
- Designed to run from any Linux environment
- Lightweight and easy to use

---

## 🛠 Requirements

- GitHub **username** and **Personal Access Token (PAT)** stored as environment variables:
  export username="your_github_username"
  export token="your_github_token"


 Usage
chmod +x list-users.sh
./list-users.sh <repo_owner> <repo_name>
 Example:
./list-users.sh Suf-sk aws-resource-tracker

What I Learned
How to work with the GitHub API

Authenticating securely using environment variables

Parsing JSON with jq

Writing user-friendly CLI scripts

Structuring a script with helper and main functions

