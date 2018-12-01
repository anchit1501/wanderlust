npm install concat --save-dev //Joind font and style.css
npm install autoprefixer --save-dev //add -webkit to all css properties so that website is compatible with older versions
npm install postcss-cli --save-dev //used with autoprefixer
npm install npm-run-all

Run Project Using npm run build:css
npm run start will run live-server and watch:sass script. Should be used while developing
npm run build:css builds the whole project. Should be used for production