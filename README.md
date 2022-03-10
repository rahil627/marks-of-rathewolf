# marks-of-rathewolf
my notes folder, now public






# todo
figure out why it's not getting the .txt files as posts  
in \_config.yml, i add the folder to defaults  
in the jekyll-optional-front-matter plugin, i forked it and try to change it so that it accepts .txt files, in addition of markdown files  
...but it doesn't work :( 
  - figured it out! but now i have a problem with encoding :(
    - the quickest solution is to simply move those files to a temporary folder \_todo-convert-to-utf8-encoding, and create a .gitignore file to ignore the folder (i won't remember if i actually add the files to the .gitignore file)
    - another solution is to have jekyll just force the encoding somehow, like trim out non-unicode characters

abstract code from layouts to includes
  - do this for both sites, this and mind
use 'group: :jekyll_plugins' in Gemfile, to avoid duplication in the config file
  - do this for *all* sites

clean up front matter in the \*-list files  
clean up the config file  
