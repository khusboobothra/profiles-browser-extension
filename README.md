## About the project 

<p align="center"><img src="https://github.com/ishubham21/profiles-browser-extension/blob/master/imgs/icon.png"></p>

A chrome extension to bring all your social media handles under one hood. Just save your profiles once and access them whenever needed.

This is a browser extension which uses browser's local storage to store all the links to your social profiles in the form of a JavaScript object. 

User can click on any icon to copy the link to the respective profile to their clipboard making it feasible for them to fill forms without having to search for each link separately.

## User Interface

This is the thought User Interface. 

<p align="center"><img src="https://github.com/ishubham21/profiles-browser-extension/blob/master/imgs/UI.png"></p>

## 🤷 Project Structure
    .
    ├── ...
    ├── js/
    │── scss/
    │── imgs/
    │── index.js
    |── manifest
    |── README
    └── ...

## Tech Stacks 
 * HTML
 * SCSS/CSS
 * Javascipt

## How to get the code running

### To visualise the browser extension, follow the following steps (Please note - since there isn't any code in manifest file, this wouldn't work as of now, you can use normal chrome to visualise the design changes) - 

 * Clone/Download this repository or fork it, as applies

 * Open chrome

 * In the address bar, type 'chrome://extensions'.

 * Enable 'Developer Mode' from the topmost-left corner (if not already provided).

 * Select 'Load Unpacked' option from the top.

 * Browse the location of the saved project and double-click the folder containing all the files.

 * You're good to go now. You'll be able to locate the extension in the extensions' section.

### Requirements

 * Browser (Google Chrome prefered)
 * Text Editor (VS Code required). Install 'Live SASS compiler' extension to work with SCSS.

### Contributing

Are we missing any of your favorite features, which you think you can add to it? We invite you to contribute to this project and make it better. You may also raise an issue.
To start contributing, follow the below guidelines: 

**1.**  Fork [this](https://github.com/ishubham21/profiles-browser-extension.git) repository.

**2.**  Clone your forked copy of the project.

```
git clone --depth 1 https://github.com/<your_user_name>/profiles-browser-extension.git
```

**3.** Navigate to the project directory :file_folder: .

```
cd profiles-browser-extension
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/ishubham21/profiles-browser-extension.git 
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream master
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Perfom your desired changes to the code base.

**9.** Track your changes:heavy_check_mark: .

```
git add . 
```

**10.** Commit your changes .

```
git commit -m "Relevant message"
```

**11.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**12.** To create a pull request, click on `compare and pull requests`. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.


**13.** Add appropriate title and description to your pull request explaining your changes and efforts done.


**14.** Click on `Create Pull Request`.


**15** Voila! You have made a PR to the awesome-developer-portfolio project. Sit back patiently and relax while the your PR is reviewed. 

 In case of any help, please free to contact me via mail @ sg2199203@gmail.com 