A ghmd-cms is an unofficial GitHub Markdown to HTML Content Management System.

### Dependencies
Name | On GitHub
---- | ----
ghmd2html | [github-markup](https://github.com/github/markup).
      | [github-markdown.](http://github.github.com/github-flavored-markdown/)

### Whats it do?

This suite of scripts will be used in being able to dynamically generate websites from a template html file and the content will be pulled in by README.md files.

The html files created in this process will overwrite the previous versions, No need to backup since your previous version is your previous git commit.

#### Some things to consider:

* I recommend adding "ghmd-cms" to the .gitignore file for your project if you clone directly into your project.

### How to use it?

If you cloned ghmd-cms into your website directory and added ghmd-cms to your .gitignore to ensure you will not re-upload ghmd-cms into your repository. This will ensure that ghmd-cms does not dirty your upload directory.

I do not suggest running ghmd2html manually. It is really just a library for update to call.

Usage is simple.

```
update
```

It scans for the README.md files and merges the template with the converted markdown as the main content of each html file. It will replace the index every time.
