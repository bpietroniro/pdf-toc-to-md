# What is this project?
Sometimes when I'm reading a long article or working through a textbook from start to finish, I like to make the table of contents into a checkbox todo list.

Why, you ask? Well, checking off boxes produces nice little microspurts of dopamine, encouraging me to keep going. It's also a way to track progress.

It's time consuming to create the list by hand (yes I've actually done this in the past), or to copy/paste headings into a Markdown file with task list formatting. So I'm working on a Python tool to accomplish the latter.

This may evolve into a tiny web app, a command line tool, or a GUI widget. But for now, here's the setup:
1. `brew install pkg-config poppler python`
2. `pip install pdftotext mistune`