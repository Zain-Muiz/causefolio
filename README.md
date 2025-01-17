<h1 align="center">
     CauseFolio
</h1>

## Description

One stop destination for showcasing the community you have built.

### Table of Contents
 
- [Tech Stack](#tech-stack)  
- [Setup and Run](#setup-run)  
  - [Setup local repo](#setup-repo)  
  - [Setup Firebase credentials](#setup-firebase)  
  - [Setup remote](#setup-remote)  
  - [Run app](#run-app)  
  - [Build app](#build-app) 
- [Contributing and PR](#contributing)   
- [Project Structure](#projectstructure)   
- [Src Structure](#srcstructure) 
- [Contributors](#contributors)

<a id="tech-stack"></a>
## ⚙️ Tech Stack

* JavaScript/TypeScript
* [NodeJs](https://nodejs.org/en/) 
* [ReactJS](https://reactjs.org/)

<a id="setup-run"></a>
## 🔨 Setup and Run

<a id="setup-repo"></a>
### Setup local repo
Let's setup the backend server on your local machine.

### 0. Prerequisites
* Install [Node.js](http://nodejs.org)

### 1. Fork repo
Fork this repo to your GitHub account  
![](https://i.ibb.co/wK4nFy9/Causefolio-fork.png)

### 2. Clone repo
Clone the forked repo to your local machine
```bash
git clone https://github.com/<YOUR-GITHUB-USERNAME>/causefolio.git
```
Navigate to project directory
```bash
cd causefolio
```

### 3. Install Dependencies
```bash
npm install
```

<a id="setup-firebase"></a>
### 4. Setup firebase for development (optional)

A firebase account is already created, but you will not have the access to it.

- To use your own firebase instance, create a new firebase project using [firebase console](https://console.firebase.google.com/).
- After creating a project, go to [project settings](https://console.firebase.google.com/project/_/settings/general/).
- In project settings of your newly created project there will be a section called 'Your Apps' which says 'There are no apps in your project, Select a platform to get started.' 
- Click on the 'WebApp' Icon, then it will ask to register a new App.
![](https://i.ibb.co/n0psH7B/Firebaseapp.png)
- In the 2nd step of app registration, firebase will provide to you the firebase credentials of your app.
- Now change it to provide your firebase credentials [here](https://github.com/codeforcauseorg/Code-for-cause-Leaders/blob/master/src/services/authService.js#L8-LL13)


<a id="setup-remote"></a>
### 5. 📡 Setup remote

0. You will have to set up remote repositories for getting latest changes from original repository
1. Specify a new remote upstream repository that will be synced with the fork using following command :
 ```bash
$ git remote add upstream https://github.com/codeforcauseorg/causefolio.git
```

2. Verify the new upstream repository you've specified for your fork using `git remote -v`
```console

origin  https://github.com/<your-user-name>/causefolio.git (fetch)
origin  https://github.com/<your-user-name>/causefolio.git (push)
upstream        https://github.com/codeforcauseorg/causefolio.git (fetch)
upstream        https://github.com/codeforcauseorg/causefolio.git (push)

```

Your application setup is successfully completed!
<a id="run-app"></a>
### Running the app

```bash
# development
$ npm run start
```
<a id="build-app"></a>
### Build Setup

- After doing changes, Run the command `npm run build` to build the app for production to the `build` folder.

```bash
# build for production
npm run build
```
<a id="contributing"></a>
### Contributions and PR

- PRs should be generated against `development`.
- Remember to run `npm run format` before creating pull request.
- Netlify willl create a preview inside pull request, Please check if your work is fine.

<a id="projectstructure"></a>
## Project Structure

    .
    ├── build                   # Compiled files
    ├── src                     # Source files
    └── ...

<a id="srcstructure"></a>
## Src Structure

    .
    ├── ...
    ├── src
    │   ├── ...
    │   ├── assets              # assets for the website
    |   ├── index.js            # starting point
    │   └── ...
    └── ...

<a id="contributors"></a>
## Contributors✨

<table>
<tr>
<td align="center"><a href="https://github.com/kunal-kushwaha"><img src="https://avatars.githubusercontent.com/u/42698533?s=100" width="100px;" alt="" /><br /><sub><b>Kunal Kushwaha</b></sub></a><br /><p>Project Head</p></td>

<td align="center"><a href="https://github.com/Abhishek-kumar09"><img src="https://avatars.githubusercontent.com/Abhishek-kumar09?s=100" width="100px;" alt="" /><br /><sub><b>Abhishek Kumar</b></sub></a><br /><p>Maintainer</p></td>

<td align="center"><a href="https://github.com/SHITIZ-AGGARWAL"><img src="https://avatars.githubusercontent.com/SHITIZ-AGGARWAL?s=100" width="100px;" alt="" /><br /><sub><b>Shitiz Aggarwal</b></sub></a><br /><p>Designer, Frontend</p></td>

<td align="center"><a href="https://github.com/mindninjaX"><img src="https://avatars.githubusercontent.com/mindninjaX?s=100" width="100px;" alt="" /><br /><sub><b>Rishabh Singh</b></sub></a><br /><p>UI/UX Designer</p></td>
<td align="center"><a href="https://github.com/AdityaTeltia"><img src="https://avatars.githubusercontent.com/AdityaTeltia?s=100" width="100px;" alt="" /><br /><sub><b>Aditya Teltia</b></sub></a><br /><p>Contributor</p></td>
<td align="center"><a href="https://github.com/mdPial"><img src="https://avatars.githubusercontent.com/mdPial?s=100" width="100px;" alt="" /><br /><sub><b>Md. Pial Ahamed</b></sub></a><br /><p>Contributor</p></td>
</tr>

<tr>
<td align="center"><a href="https://github.com/rizwan2000rm"><img src="https://avatars.githubusercontent.com/rizwan2000rm?s=100" width="100px;" alt="" /><br /><sub><b>Rizwan Memon</b></sub></a><br /><p>Contributor</p></td>

</tr>
</table>

