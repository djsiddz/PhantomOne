# PhantomOne
My first attempt at creating a theme for Ghost. I have set up Ghost locally on my machine and I have created a new theme folder `phantomOne`.

I will be spending some time reading the Casper theme code to understand how themes function in Ghost. There are two options from here - either I use Casper as my base theme or else I code from scratch.

I will be coding from scratch. As per the advice on the [Ghost Theme Documentation](http://themes.ghost.org/docs/getting-started), I'll be creating the theme using HTML and CSS first and then converting it to a Ghost theme.

The file structure for any theme is as listed [here](http://themes.ghost.org/v0.7.5/docs/structure). For reference, I'm also adding the same structure here.

```
.
├── /assets
|   └── /css
|       ├── screen.css
|   ├── /fonts
|   ├── /images
|   ├── /js
├── default.hbs
├── index.hbs [required]
└── post.hbs [required]
└── package.json [required]
```
