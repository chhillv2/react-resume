This repo contains the code that is used to create my resume site [jonbloomer.com.au](http://jonbloomer.com.au).  I used Facebook's excellent boilerplate [Create React App](https://github.com/facebookincubator/create-react-app) and enhanced it with the extra tools that I needed.

The whole application is based around this file `/src/resume.json` which is structured using the schema from [jsonresume.org](https://jsonresume.org/schema/). In `src/components/App.js` I think import this json object and assign each section to a data variable which is then passed in as a prop to the corresponding section component such as `src/components/About.js`.

Once its done, it is converted to pdf.
Run yarn install (or npm install)

Run create-react-app in development mode: yarn start (or npm start)

Open http://localhost:3000 to view it in the browser.

Edit src/

Export PDF: yarn pdf (or npm run pdf), Make sure you run it in different terminal while server is running.

Generated resume is in: out/resume.pdf

[![Donate with Bitcoin](https://en.cryptobadges.io/badge/big/15H4Wbpmqa6rp8wLRP2atWVhfemUhKjHbn)](https://en.cryptobadges.io/donate/15H4Wbpmqa6rp8wLRP2atWVhfemUhKjHbn)
