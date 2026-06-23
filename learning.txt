#how claude code works
Understand task
↓
Inspect repo
↓
Find relevant files
↓
Plan change
↓
Edit files
↓
Run command/test
↓
Read output
↓
Fix if needed
↓
Summarize

#example 
You: Find why login API fails when email is missing and fix it.

Claude Code:
1. Searches the repo for login route.
2. Opens relevant files.
3. Finds validation logic.
4. Edits the schema or controller.
5. Runs tests.
6. If tests fail, reads the error.
7. Fixes again.
8. Gives final summary.

# the final verdict == Claude Code = Claude + project files + terminal commands + edit ability + feedback loop.

#Basic commands to work with 
1. to start claude in current project
claude
2.giving claude a direct task 
claude "explain the current repo"
3. to check available options 
claude --help
