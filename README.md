# World Affairs Conference Landing Page
The landing page for WAC, which functions as a coming-soon page.

As a note, my final goal is to use a version of [liteweight](https://github.com/malsf21/liteweight) or some other custom scss instead of Bootstrap since we don't need the vast majority of its bloat. The current template is here just to get a feel of things.

We use grunt as a task runner, though it doesn't really do too much. You can install it with:

```
npm install
npm install -g grunt-cli
```

In development, you can use this to update your CSS to match changes in SCSS.

```
sass --watch css
```

To perform a one-time compile, use

```
grunt
```
