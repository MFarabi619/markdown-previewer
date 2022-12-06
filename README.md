# markdown-previewer
 A little web app that renders a live preview of Markdown

 [Live Demo](https://markdown-previewer-mfarabi.vercel.app/)
 ![Image][https://i.ibb.co/s2bNzHg/Screenshot-2022-12-06-012822.jpg]

## Learning log for this project
* Used [Vite](https://vitejs.dev/) to set up project instead of [create-react-app](https://reactjs.org/docs/create-a-new-react-app.html)
  * This is because create-react-app became cumbersome and clunky while working on the [random quote machine](https://github.com/Mfarabi619/random-quote-machine) project 
* Initial project setup with Vite:
  * Ran '$ npm create vite@latest'
  * Selected react template
  * Ran 'cd markdown-previewer'
  * Ran 'npm install'
  * Ran 'npm run dev'
* Learned Git console commands which sped up development
  * Was previously using GitHub Desktop to commit and push changes
  * Created a separate development branch in order to follow better practices
* Learned more Vim commands to speed up development
* Ran 'npm install react-markdown' for markdown parser instead of marked.js due to security issue with dangerouslySetInnerHTML
* [Steps](https://vitejs.dev/guide/static-deploy.html) for deploying on [Vercel](https://vercel.com/). Got an error for running scripts disabled on the system, fixed it by following [this](https://www.roelpeters.be/solved-running-scripts-is-disabled-on-this-system-in-powershell/).