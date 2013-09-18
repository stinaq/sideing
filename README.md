#Sideing

Greyshade is a minimal, responsive theme for Octopress.
Starting point forked from [Greyshade](https://github.com/shashankmehta/greyshade)  

##Install

Assuming you have installed the default theme, type the code below in terminal.

    $ git clone git@github.com:shashankmehta/greyshade.git .themes/sideing
    $ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with your highlight color
    $ rake "install[sideing]"
    $ rake generate

For profile picture and description, just add the relevant details in `_config.yml`
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
