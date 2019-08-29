# mcdomx.github.io
Mark McDonald Source Page

https://mcdomx.github.io


After installing bundler and jekyll, the following were necessary to fix bundle version error:
(https://stackoverflow.com/questions/53231667/you-must-use-bundler-2-or-greater-with-this-lockfile)
    You must use Bundler 2 or greater with this lockfile.
    
    gem update --system
    bundler update --bundler

jeckyll build
    - builds _site

jeckyll serve
    - builds _site that can be viewed at http://localhost:4000
    
To add new project's:
	- update /data/projects.yml
	- add new page for the project in /project_pages/<project_name>.html
	- update the new html page with front matter variables
