Steps to Make a GitHub Page Markdown
===========

1. Create the _config.yml file with "markdown: kramdown"
2. Create _includes folder with header.html file with all of header up to and including the first section tag.
3. Create footer.html file in _includes folder with all of footer including closing section tag.
4. Create _layouts folder and add main.html for the jekyll bot.
5. Edit index.html file to index.md, add header instructions --- then new line "layout: main" then new line "published: true" then new line --- three dashes.
6. You should also create a .gitignore file with two lines in case you ever download and run the site locally: .DS_Store and _site
