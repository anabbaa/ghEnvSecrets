# where to add environemnt variables

- you can add them in the top with level of name and on so the whole file can read it unless a job overwrite it or even you can add it for a certain job or even a step
- you will add a reserved word env inside it add the name of environment variable as a key and assign to its a value
- to add environment variable to any link for server for example add before it $ for linuk devives or use context env

# ghEnvSecrets

- if you have organization account you can store them in organization level
- you can go to your reposoitory setting under security actions secrets you cam add them name it and gives it a value
- you can add your serets to environment in your repository setting under environment only if your repo is public you attach them to your repo and workflow job can reference to them you can also add more protection rules
  - create new environment you can add specific secrets to it then add environment reserved word to your job and write as a value its name you can add reviewers timer and choose which branch will use them
