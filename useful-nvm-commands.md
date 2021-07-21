## Install Node
```
nvm install <node_version>      // Install a specific Node version
nvm install node                // Install latest Node release (Current)
nvm install --lts               // Install latest LTS release of NodeJS
nvm install-latest-npm          // Install latest NPM release only
```

### List Available Node Releases
```
nvm ls-remote
nvm ls-remote | grep -i "latest"        
nvm ls-remote | grep -i "<node_version>"
```

### List Installed Nodes
```
nvm list node                   // Lists installed Node versions
nvm list  (or)  nvm ls          // Lists installed Node versions with additional release info
```

### Switch To Another Node Version
```
nvm use node                      // Switch to the latest available Node version
nvm use <node_version_or_alias>  // Switch to a specific version
nvm use --lts                    // Switch to the latest LTS Node version
```

### Verifying Node Version
```
node -v  (or)  node --version
npm -v   (or)  npm --version
nvm -v   (or)  nvm --version
```

### Set Alias
```
nvm alias default node                  // Always defaults to the latest available node version on a shell
nvm alias default <node_version>        // Set default node version on a shell
nvm alias <alias_name> <node_version>   // Set user-defined alias to Node versions 

nvm unalias <alias_name>                // Deletes the alias named <alias_name>
```

### Path to Node Executable
```
nvm which <installed_node_version>      // path to the executable where a specific Node version is installed
```

### Uninstall Specific Node Version
```
nvm uninstall <node_version>    // Uninstall a specific Node version
nvm uninstall --lts             // Uninstall the latest LTS release of Node
nvm uninstall node              // Uninstall latest (Current) release of Node
```

### Uninstall NVM
```
 To remove, delete, or uninstall nvm, just remove the $NVM_DIR folder (usually ~/.nvm)
```
