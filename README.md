# firebase
Using firebase for hosting a static website.<br>
steps:<br>
. create a project in firebase console.<br>
. install firebase cli using npm from your terminal : npm install -g firebase-tools <br>
. after installing type in terminal : firebase login 
. now move to the directory of your website to be hosted and use : firebase init<br>
. select your project you created on firebase and choose hosting option <br>
. select N for public folder and proceed <br>
. files namely .firebase,firebase.json and a public folder with 404.html and index.html added<br>
. now move all your static files into that public folder and delete the existing index.html in it<br>
. good to go , now deploy using : firebase deploy<br>
you will have your hosting url like : https://real-esta.web.app <br>
