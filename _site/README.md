# mcdomx.github.io
Mark McDonald Source Page

https://mcdomx.github.io


After installing bundler and jekyll, the following were necessary to fix bundle version error:
(https://stackoverflow.com/questions/53231667/you-must-use-bundler-2-or-greater-with-this-lockfile)
    You must use Bundler 2 or greater with this lockfile.
    
    gem update --system
    bundler update --bundler

Built the site:
    
    jekyll build
    
Run the site and view at http://localhost:4000
    
    jekyll serve
    
    
To add new project's:
    
1.  Create a project page for the project
2.  Copy an application screenshot to `static/images`
3.  Copy an existing project md template in `_projects/`.  Each md file will be used to create a link to a new project site automatically.  No need to update any HTML.  Just add the new md file to include new projects.
4.  Rename the template to the repo name of the project
5.  Update the md fields with relevant project information
	
