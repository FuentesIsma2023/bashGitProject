🛠️ GitHub Authentication Troubleshooting
While working on this project, I encountered the following error when trying to push changes to GitHub:
remote: {"auth_status":"auth_error","body":"Invalid username or token. Password authentication is not supported for Git operations."}

✅ How I resolved it:

I navigated to Settings > Developer settings > Personal access tokens in GitHub.
Selected Tokens (classic).
Since I wasn’t sure which permissions were required, I enabled all available scopes to ensure full access.
I used the generated token as the password when prompted during git push.

This resolved the authentication issue successfully.
