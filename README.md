> A template for E-commerce web app.

## Creating a Vue webpack project
``` bash
1. vue init webpack <project-name>
2. cd <project-name>
3. npm run dev
```

## Bootstrap
[How to include the  Bootstrap with Webpack](https://stevenwestmoreland.com/2018/01/how-to-include-bootstrap-in-your-project-with-webpack.html)
```bash
#install Bootstrap,JQuery and popper.js
npm i bootstrap jquery popper.js --save
#import bootstrap javascript in the entry file
import 'bootstrap'
#scss file in /assets
Create a .scss file in the assets
#import all of Bootstrap's Sass in to the .scss file
import '~bootstrap/scss/bootstrap'
#import the .scss file in to the entry file
import '@/assets/main.scss'

```