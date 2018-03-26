# Welcome to Mockup of template of Dokify Dashboar!

Hi, here I leave a small template that mock up for a test that I was asked to do the **Dokify** company where I was asked to develop a dashboard of one of their applications.

This mock up was made with the help of "NPM Install" to use gulp and its benefits such as SASS, as well as a series of dependencies, google icons and other things.

It is also important to note that it has a structure of 12 columns in its layout to facilitate the work of grids and It should also be noted that all these classes were generated dynamically with the SASS mixins to automate the work.

# Files or Structure

has a simple structure to understand with the folders Css, JS, IMG, SASS, VENDORS, and the file index.html all the style files are in the SASS folder and its main file is called admin.scss.

# Usage file with NPM

To use and update from sass just you need it is to use the comman line:

    $ npm install
  
  and then that dependencie was installed you need run:
  
    $ gulp dev
   
   this go to help you to watch the modification on de `index.html` file and `*.scss` files.
 
  
#### Gulp Tasks available in the project

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css:compile` compiles SCSS files into CSS
- `gulp css:minify` minifies the compiled CSS file
- `gulp vendor`  copies dependencies from node_modules to the vendor directory

I hope it helps you in something. 
See You...