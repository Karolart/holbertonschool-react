# 0x01. React intro  
___________________________________________________________  
![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2019/12/79df527164ac54981039.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20221228%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20221228T133013Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e1188f18dce259497b618773334c957dc1413f89289b6c040a410d9ebd1359f6)  
  
## Tasks  
  
** 0. Basic application **  
- Create a basic app named dashboard using create-react-app in your task_0 directory  
________________________________________________________________________________  
** 1. Embedding expressions, functions **  
- Using your code from the previous task, in task_1/dashboard/src/utils.js  
________________________________________________________________________________  
**2. Modify the App**  
- using your code from the previous task, in task_2/dashboard/src/App.js under the paragraph that says Login to access the full dashboard  
_________________________________________________________________________________  
**3. Modify the Notifications**  
- in task_2/dashboard/src/utils.js  
_________________________________________________________________________________  
**4. Create basic tests with four tests**  
- in task_3/dashboard/src/utils.test.js  
_________________________________________________________________________________  
**5. Install Enzyme**  
- Install Enzyme with npm  
- Create a file named setupTests.js and configure the adapter for Enzyme  
__________________________________________________________________________________  
**6. Create React tests**  
- n task_3/dashboard/src/App.test.js create four tests  
__________________________________________________________________________________  
**7. Deploy to a GitHub page**  
- Deploy your application to GitHub Pages using gh-pages branch and create-react-app

Your application should be working correctly when accessing the GitHub URL.  
___________________________________________________________________________________  
**8. Create a project using Webpack**  
- Without reusing create-react-app or the code from the previous exercise, start a brand new npm project

Reusing what you learned during the Webpack module  
____________________________________________________________________________________  
**9. Install Babel**  
- Install Babel, and in task_5/dashboard/.babelrc, add the presets for preset-env and preset-react  
- Add a babel-loader to the Webpack configuration so you can support js and jsx files  
- Import the files that you wrote in the previous task. All the Javascript and React code should be within the src folder  
_____________________________________________________________________________________  
**10. Reorganize the files**  
- Let’s reorganize the files in our project:  
  
Every file related to the App, should be within a App folder  
Every file related to the Notifications, should be within a Notifications folder  
Every file related to the utils functions, should be within a utils folder  
Every asset file should be within the assets folder  
Set up the favicon.ico in the dist folder  
Webpack config file should be within a config folder if it isn’t already  
______________________________________________________________________________________  
