# Installing node on WSL ubuntu distro

1. Install nvm with: `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash`
2. Close and reopen terminal
3. Install node LTS version with: `nvm install 20.10.0` or any LTS version that is currently available.
4. `node --version` or `node -v` to display version of node

uninstalling nvm

---

- `nvm use system`
- `npm uninstall -g a_module`

i'm not sure if the above command will work, either way👍
