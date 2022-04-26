"# challenge-sass" 
Published Url : https://snehalchetan.github.io/challenge-sass/


Install Sass with the instructions :
https://sass-lang.com/install

After the installation type sass -v in the console, it should display the latest version.

If you are using Phpstorm, the moment you create a .scss file, it will offer you to manage SASS compilation for you, you can accept this. In PHPSTORM this is called a file watcher, you can always edit the settings in file -> settings -> file watcher -> scss.

If you are using another editor you have to run commands to watch the files

sass --watch input.scss output.css (single file)

sass --watch app/sass:public/stylesheets (entire directory)

(Optional) Make Phpstorm write .css file to different directory
On default Phpstorm writes your CSS file to the same directory as your SCSS file. In a bigger project you probably want to write your CSS files to a different directory like css/ to keep everything organised.

You can do that with the following changes in file -> settings -> file watcher -> scss:

Arguments:
--no-cache --update $FileName$:$ProjectFileDir$/css/$FileNameWithoutExtension$.css

Output path to refresh: $ProjectFileDir$/css/$FileNameWithoutExtension$.css:$FileNameWithoutExtension$.css.map

Useful Learning links :

https://sass-lang.com/documentation/interpolation

Video to learn SASS:
https://www.youtube.com/watch?v=Zz6eOVaaelI

Minify Stylesheet:
https://hoohoo.top/blog/20210703113717-how-to-customerize-the-live-sass-compiler-settings-for-output-formats/