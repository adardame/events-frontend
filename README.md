# Amarillo Even Hub Frontend

**(from: Webpack + SASS + Handlebars + Dev Server Boilerplate)**

## Getting Started

run:
`npm install`

The _SASS/SCSS_ code goes inside the styles directory.

The _JS_ code goes inside the app directory.

The _Handlebars_ files goes inside the templates directory.

## Changes in real time

1. Start the _Webpack Dev Server_:
`npm run dev`

2. Go to the url:
`http://localhost:8080/webpack-dev-server/`

3. Start to code and see the magic happens.

4. After you finish the development, run the next command to have all your code available and minified in your build directory:
`npm run build`

## Deployment

Right now, this repository is tied to continuous deployment for https://amarilloeventhub.com, so any push to the Master branch will automagically be published to the site. The backend is [in another repository](https://github.com/AmarilloTechMeetup/events-backend), and that does not yet have a Continous Deployment hook. We'll add one once we have things tied together end-to-end. 
