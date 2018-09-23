# NG_6-NGB_4-BT_5-FA-5
angular 6, bootstrap 5, ngBootstrap 4, FontAwesome 5

1. Setup a new basic Angular 6 project using CSS
   a) ng new my-angular-app --style=css --routing --skip-tests
   b) cd my-angular-app
   
2. Integrate Bootstrap 5 in the latest Angular project
   a) npm install bootstrap
   b) Then go to angular.json file and add the following lines of code in styles array to include the bootstrap 5 css in your app.
   "styles": [
      "./node_modules/bootstrap/dist/css/bootstrap.min.css",
    ],
   
3. Integrate NG-Bootstrap4
   a) npm install --save @ng-bootstrap/ng-bootstrap
   b)
   
   
4. Add Font Awesome5 icons set in the Angular6 CLI project
   a) npm install @fortawesome/fontawesome-free-webfonts
   b) Then go to angular.json file and add the following lines of code in styles array to include the Font Awesome5 icons set in your app.
   "styles": [
          "node_modules/@fortawesome/fontawesome-free-webfonts/css/fontawesome.css",
          "node_modules/@fortawesome/fontawesome-free-webfonts/css/fa-regular.css",
          "node_modules/@fortawesome/fontawesome-free-webfonts/css/fa-brands.css",
          "node_modules/@fortawesome/fontawesome-free-webfonts/css/fa-solid.css"
   ]
   
   Afterwards, You can easily use any Font Awesome5 icons in your project.

   Just visit Font Awesome5 website and search for any free icon you’d like to use in your project.
   
   c) Search on icon 
   d) Copy the icon code from FontAwesome5 website. "<i class="fab fa-angular"></i>"
   e) Go to your any app.component.html file and paste the given below code.
      <i class="fab fa-angular"></i>
