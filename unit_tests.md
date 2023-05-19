## Jasmine
### Pros
- Fast with no dependencies
- Available for Node.js and the browser
- Easy syntax
### Cons
- Requires many configurations
- Difficulty with asynchronous testing
- Difficult to integrate snapshot testing

## Cypress
### Pros
- Uses real browser to run tests, which considers the specific quirks that affect code execution
- Has access to network layer, allowing control for all requests
- Can take screenshots and videos during test for easy replay
### Cons
- Only supports JS
- Does not support multiple tabs or windows
- Cannot visit two domain names in the same test

## Puppeteer
### Pros
- Well documented and user-friendly
- Can run parallel tests
- Supports screenshot and pdf generation
### Cons
- Requires Node.js experience
- Stunted performance with complex webpages
- Only supports latest version of browsers
