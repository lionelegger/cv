# Lionel EGGER Starter Kit

## Installation

Firstly, be sure you have the following installed: 
### Node (node.js)
- The JS library for running web applications
- Check version with `node -v`
- Installation on https://nodejs.org/en (node.js and npm)

### Gulp. 
- Helps out with several tasks when it comes to web development (spinning up web server, reloading browser, scss, minification, etc)
- Check version with `gulp -v`
- Install with `sudo npm install gulp-cli -g`


1. Clone the project with `git clone https://github.com/lionelegger/bootstrap-starterkit.git`
2. Install all dependances with `npm install`

<br/>

## Execution

- Working files are in the 'src' folder: CSS, JS and VIEWS
- css and js gets minified automatically

**DEVELOPEMENT**
- `gulp` will autocompile all assets in a 'dist' repository with **browsersync** and run a local server `http://localhost:8080/` 
- `gulp build` will put all in the root folder (with folder css, js and img). 
- Commit in the gitHub Repository, set up as "open" and rendered as a page. The URL will be https://lionelegger.github.io/cv/



