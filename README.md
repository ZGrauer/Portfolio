# Portfolio Website
----

### What is it?
A responsive website to display completed portfolio projects, along with work experience and education. Built using the [Bootstrap framework](http://getbootstrap.com/).

### Installation
1. Download and install [Node.js](https://nodejs.org/en/download/) using these [instructions](https://docs.npmjs.com/getting-started/installing-node).
2. Download and install [GitHub Desktop](https://help.github.com/articles/set-up-git/) using these [instructions](https://help.github.com/articles/set-up-git/)
3. Clone this repository using the [instructions from GitHub](https://help.github.com/articles/cloning-a-repository/)
    * Ensure you use command:
        ```
        $ git clone https://github.com/ZGrauer/Portfolio.git
        ```
4. Install all dependencies by entering `npm install` from a command line within the cloned folder.
5. Edit HTML and CSS files as needed.

### Development
Modify the site as needed but be sure to edit the non-minified files. Edit the files that do not contain *min* in their names and create the *min* versions using Grunt. Additionally, save raw, large images to the *src* folder and use grunt to minify them for you.

Open your favorite Terminal and run these commands.
```sh
$ grunt cssmin
```

```sh
$ grunt imagemin
```

`cssmin` creates **.min.css* versions for all the files within the *css* folder.
`imagemin` creates new, optimized versions of all images in the *src* folder. The new images are saved to folder *images*.

### Todos
- [ ] add 2 additional projects, replacing Project 2 and Project 3
- [ ] hover effect for project thumbnail
- [X] Zocial GitHub and LinkedIn buttons in Contact aside

### License
GNU GENERAL PUBLIC LICENSE
