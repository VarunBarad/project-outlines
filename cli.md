# Blog Helper

- Should be able to generate a new TIL post after taking title and description and open the newly created file in default editor.
  - Accept title and/or description as part of cli args `--title -t` and `--description -d`
  - If not supplied via cli args then dynamically ask users for inputting title and description
- Read env vars (location of blog repository)
- Capture user input (mentioned above)
- Check existence of a file
- Create a file
- Write to that file
- Execute shell commands (opening the file in default editor)