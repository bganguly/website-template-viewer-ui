# README for branch_04 #

This project requires us to develop a website template viewer. See details in [README.md in master branch](https://github.com/bganguly/coding-project-ui/tree/master#readme) 

This specific branch builds on top of branch_03 on the UI and, as stated there , continues to rely on the express app runnable via checking out the [backend project / branch_03 branch](https://github.com/bganguly/coding-project-backend/tree/branch_03).  
This branch does some simplification by reducing the props to one of the child components and makes the UI more intuitive, by automatically showing the first large image,
as the prev/next buttons- pull in prev/next thumbnails on the screen.  
More instructions follow.

To run:
```
// startup the express server first
// git clone and checkout the backend branch_03 branch , thereafter
rm -rf package-lock.json ; rm -rf node-modules/ ; npm i
npm start

// bring up the React app next
// git clone and checkout this current branch_04 branch, thereafter
rm -rf package-lock.json ; rm -rf node-modules/ ; npm i
npm start
```