# Docker How To
Presentation uses reveal.js [reveal.js](https://github.com/hakimel/reveal.js)

See also [examples](https://github.com/patrykomiotek/docker-how-to/tree/master/examples) folder

## Setup

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)
