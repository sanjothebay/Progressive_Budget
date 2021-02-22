# Progressive_Budget

https://sheltered-headland-18484.herokuapp.com/

https://sanjothebay.github.io/Progressive_Budget/

https://github.com/sanjothebay/Progressive_Budget


![image](https://user-images.githubusercontent.com/67298961/108643250-6505c180-746f-11eb-8fe3-f1cd954453fd.png)


# Table of contents

1. [Instruction](#Instruction)
2. [Getting Started](#Getting_Started)
3. [Service-worker](#Service-worker)
4. [Routes](#Routes)
5. [Submission Video](#Submission_Video)
6. [LICENSE](#LICENSE)


## Instruction <a name="Instruction"></a>

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Getting Started <a name="Getting_Started"></a>

running npm init from the command line.
npm install To added the dependancies:
The application will be invoked by using the following command:

```
npm start To run the App
npm run test To run the tests 
npm webpack To run webpack --watch
npm build To run npm run webpack
npm lite-server To run lite-server
```


## Dependancies

```
  "dependencies": {
    "compression": "^1.7.4",
    "express": "^4.17.1",
    "glob": "^7.1.4",
    "lite-server": "^2.5.3",
    "mongoose": "^5.5.15",
    "morgan": "^1.9.1",
    "webpack": "^4.32.0",
    "webpack-cli": "^3.3.2",
    "webpack-pwa-manifest": "^4.3.0"
  }
```

#### Directory structure
Directory structure <a name="Directory_structure"></a>

All the recommended files and directories structure:

```
.
├── models
│   └── transaction.js
│  
├── pulic
│   ├── icons
    │   ├── icon-192x192.png
│   │   └── icon-512x512.png
│   ├── index.html
│   ├── index.js
│   ├── indexedDB.js
│   ├── manifest.webmanifest
│   ├── service-worker.js
│   └── styles.js
│
├── routes
│    └── api.js
│ 
├── .gitgnore
│ 
├── package-lock.json
│
│── package.json
│
├── README.md
│
└── server.js
```


## Service-worker <a name="Service-worker"></a>

![image](https://user-images.githubusercontent.com/67298961/108652314-722faa00-7489-11eb-9e4f-488db300ed6e.png)


Running Service Worker.

![image](https://user-images.githubusercontent.com/67298961/108659054-3fd57b00-7490-11eb-8cf8-071d8d111d4f.png)


## Routes <a name="Routes"></a>

![image](https://user-images.githubusercontent.com/67298961/108654079-8bd2f080-748d-11eb-82be-17ee96099681.png)

## Submission Video <a name="Submission_Video"></a>


## LICENSE <a name="LICENSE"></a>

License under the [MIT License](LICENSE)
