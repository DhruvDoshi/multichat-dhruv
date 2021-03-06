<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/v5kXT8t.png" alt="Bot logo"></a>
</p>

<h3 align="center">multichat-dhruv</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/DhruvDoshi/multichat-dhruv.svg)](https://github.com/DhruvDoshi/multichat-dhruv/issues)
[![HitCount](http://hits.dwyl.io/DhruvDoshi/multichat-dhruv.svg)](http://hits.dwyl.io/DhruvDoshi/multichat-dhruv)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/DhruvDoshi/multichat-dhruv.svg)](https://github.com/DhruvDoshi/multichat-dhruv/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Multiple Users could chat over the platform
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [How it works](#working)
- [Usage](#usage)
- [Getting Started](#getting_started)
- [Deploying your own platform](#deployment)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

With the help of this platform multiple users could have a video chat. This platform doesn't saves any single bit of data on the servers. We only present the video and completely delete it


## 💭 How it works <a name = "working"></a>

The platform extracts the data with Webrtc Api and the it connects the users throught that api, continuing with that we are adding multiple modes and filters for the users.

The app is designed to take only 2 users as the time and others will wait their way in the waiting room until the conversation is over.

The entire application is written in JavaScript

## 🎈 Usage <a name = "usage"></a>

The application is hosted over the heruku and the like is listed in the description.


## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
  - [Node.js](https://nodejs.org/) v4+
  - [Python 3](https://python.org/) v3.6+
  - [Git ](https://git-scm.com/) v2.26.0+
  - [pip ](https://pip.pypa.io/en/stable/) v19+
  - [Docker ](https://docs.docker.com/release-notes/) v19.03.8+
 
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
git clone https://github.com/DhruvDoshi/multichat-dhruv
cd multichat-dhruv
npm install
npm start 
```


## 🚀 Deploying your own application <a name = "deployment"></a>


#### Changing your App name on Heroku <a name="changing_your_app_name_on_heroku"></a>
You can rename an app at any time with the ```heroku apps:rename command```. For example, to rename an app named “oldname” to “newname”, run the ```heroku apps:rename``` command from your app’s Git repository:
```
$ heroku apps:rename newname
Renaming oldname to newname... done
http://newname.herokuapp.com/ | git@herokuapp.com:newname.git
Git remote heroku updated
```

You can also rename an app from outside of its associated Git repository by including the ```--app``` option in the command:
```
$ heroku apps:rename newname --app oldname
http://newname.herokuapp.com/ | git@herokuapp.com:newname.git
```

## ⛏️ Built Using <a name = "heroku"></a>

- [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ Authors <a name = "authors"></a>

- [@DhruvDoshi](https://github.com/DhruvDoshi) - Idea & Initial work

See also the list of [contributors](https://github.com/DhruvDoshi/multichat-dhruv/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Inspired by Government news on Zoom hiding data
- References
