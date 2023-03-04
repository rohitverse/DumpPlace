
# Click Here 

<img width="307" alt="image" src="https://user-images.githubusercontent.com/67726628/222915524-9b57c8ac-62ff-4056-be40-e56434e2d889.png">

# search eslint and scroll down click on edit settings.json

<img width="606" alt="image" src="https://user-images.githubusercontent.com/67726628/222915589-34dd23aa-9f31-457d-8bab-98c7b5d84e77.png">


# Copy and paste below code in settings.json file and save it

```
{
  "workbench.iconTheme": "material-icon-theme",
  "solidity.telemetry": true,
  "editor.formatOnSave": true,
  "git.autofetch": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "never",
  "prettier.singleQuote": true,
  "editor.wordWrap": "on",
  "editor.codeActionsOnSave": {
  
     "source.fixAll.eslint": true
  },
  "eslint.validate": [
        "javascript"
      ],
  "eslint.workingDirectories": [
        "./client",
        "./server"
      ],
  "files.exclude": {
        "**/.git": false,
      },  
  "tailwindCSS.emmetCompletions": true,
  "[solidity]": {
    "editor.defaultFormatter": "JuanBlanco.solidity"
  },
  "solidity-language-server.trace.server.verbosity": "message",
  "eslint.codeActionsOnSave.rules": null,
      
}

 ```
