# Nightwatch

- Automated end-to-end testing framework powered by Node.js and using W3C Webdriver (formerly Selenium).
- Nightwatch is a complete and integrated solution for end-to-end testing of web applications and websites. It can also be used for Node.js unit and integration testing.[nightwatchjs.org]

# Install

- Clone this repo
- Install node packages `npm install`
- Run all tests `npm test`

# Tips

- Error on Ubuntu 20.04 while using older chrome v 93.x: An error occurred while retrieving a new session: "session not created: This version of ChromeDriver only supports Chrome version 95"
  - Solution : Update chrome to latest version
- Further reading, (if error nightwatch.json not found, just create an empty file at root directory)

```
    git clone https://github.com/nightwatchjs/nightwatch.git
    cd nightwatch
    npm install
    npm test

```
