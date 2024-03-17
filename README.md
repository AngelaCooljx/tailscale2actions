# tailscale2actions
SSH to GitHub Actions VM using Tailscale

Now supports: Ubuntu, MacOS

## How to use
1. Install Tailscale in your local client and log in

2. Fork this repository

3. Add a repository secret in "Settings" - "Secrets and Variables" - "Actions" - "Repository Secret" with the name "SSH_PASSWORD" and type your password

4. Run and check workflow. Visit `https://login.tailscale.com/a/xxxxxx` to authenticate

5. Connect to GitHub Actions VM via `ssh [username]@[tailscale-ip]`

## Credits
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [Tailscale](https://tailscale.com)