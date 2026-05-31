### Cursor IDE Setup and GitHub Repository Task

## Tools Installed

* Cursor IDE
* Claude Code Extension in Cursor
* Codex Extension in Cursor
* Git for windows

## Steps Completed

1. Installed Cursor IDE
2. Installed Claude Code extension in Cursor
3. Installed Codex extension in Cursor
4. Created a public GitHub repository
5. Installed Git for windows
7. Opened the repository in Cursor
8. Created README.md file
9. Committed and pushed the repository to GitHub

## Issues Faced and Solutions

### Git Command Not Recognized

While trying to clone the GitHub repository, the following error occurred:

```powershell
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable program.
```

This happened because Git was not installed on the system.

**Solution:**
Installed Git using the following command:

```powershell
winget install --id Git.Git -e --source winget
```

After installation, restarted the terminal and successfully cloned the repository.

## Remarks

This is my first time in using Cursor IDE, Still i need to research more about the use case of cursor and how it can help me in future endeavors. 

I have used AI to refine the wordings in the README file, but the thought process behind it were mine. 



