# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package.json file holds all of the relevant metadata for the project.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json file needs to exist in the root, easily accessed before anything else.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build?
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Environment variables
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view build logs from when your project is being built, or runtime logs. The command heroku logs fetches your most recent logs.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You need to add the heroku repository to your project, and git push heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching helps keep code from being overwritten. It also helps in the event of an issue to be able to easily roll back a branch merge without affecting any other merges.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
I think generally right before you merge a branch into it's parent.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```
