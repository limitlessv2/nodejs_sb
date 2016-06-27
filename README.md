# nodejs_sb
node js vagrant sandbox


Useful commands

Start a new project
express $project_name


> cd $project_name

Now about adding dependencies
edit the package.json file 

remove 
	jade

add 
	"hjs": "~4.0.5" ,
	"less-middleware": "0.1.15"

Download dependencies
> npm install

About running the app

> SET DEBUG=$project_name:* 
> npm start

or 

>nodemon bin/www