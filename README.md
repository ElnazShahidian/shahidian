# [Shahidian](http://shahidian.com)
This is a boilerplate for a personal website. It's designed to be beginner friendly to be used as a start point. Some approaches are old fashion, but the choice is made for ease of on-boarding.

## Getting started

You need:

- [git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/package/npm)
- [http-server](https://www.npmjs.com/package/http-server)

before you start. Once you have them ready, clone the project
```
git clone https://github.com/ElnazShahidian/shahidian.git
```
and then run

```
http-server .
```
or equivalently
```
npm start
```

The project will be served at `http://localhost:8080`. Open this on your browser.



### What's in the repo?

The download includes Skeleton's CSS, Normalize CSS as a reset, a sample favicon, and an index.html as a starting point.

```
Skeleton/
├── index.html
├── css/
│   ├── normalize.min.css
│   └── skeleton.css
└── images/
    └── favicon.ico

```

### Why it's a good start point
- The structure is super simple.
- It gives you the opportunity to use git.
- It introduces the concept task runners (bower).
- It comes with package.json file to introduce npm scripts.


### To upload the changes

Use git to upload the changes to the repo

1. Receive the latest changes (pull from the repo)
```
git pull origin master
```

2. Add new changes
To add all the changes at once, run
```
git add .
```
or to add certain file or directory, run
```
git add ./css
``
Where you add all files in `/css` directory. you can also add only one file by running:
``
git add ./css/styles.css
```
Which adds only `./css/styles.css` file.


3. Add a commit message
```
git commit -m 'Changed some styles'
```
In the above command, `-m` stands for message and you can add any message as long as you wrap it in single or double quotations.

4. Upload changes (push to the repo)
```
git push origin master
```
