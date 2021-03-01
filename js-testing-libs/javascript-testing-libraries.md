# JavaScript Testing Libraries

## Overview

1. Unit Test: to examine each small piece of codes, testing primitive components in the life cycles
2. Integration Test: to test how components interact with each other, testing composed components, by mocking your endpoints
3. End-to-end Test: to test the whole system with real data

## Comparison of testing frameworks

1. Puppeteer: a Node library providing browser automation for chrome and chromium
   <p>Puppeteer runs headless by default, but can be configured to run full (non-headless) Chrome or Chromium; It provides a high-level API to control Chromium or Chrome over the DevTools Protocol</p>
2. Jest: a unit testing framework focused on simplicity
   <p>This is a Unit test framwork especially designed for the React.JS, Babel, TypeScript, Node, React, Angular and Vue projects. It usually worked with Enzyme(Integration testing)</p>
3. Enzyme: a JS testing utility framework, maintained by Airbnb
   <p>Enzyme enables you to:
      Use shallow rendering
      Access business implementations of your components
      Conduct full DOM renderingUse react-hooks in shallow rendering, with some limitations</p>

| Differences     |     Puppeteer      |                                                 Jest |
| :-------------- | :----------------: | ---------------------------------------------------: |
| Category        | Browser Automation |                                         Unit Testing |
| xUnit           |         No         |                                                   No |
| Client-side     |        Yes         |                                                  Yes |
| Server-side     |         No         |                                                  Yes |
| Fixtures        |        N/A         |                                                  Yes |
| Group Firxtures |        N/A         |                                                  Yes |
| Generators      |         No         |                                                  N/A |
| License         | Apache License 2.0 |                                          MIT License |
| Mocks           |         No         | a custom resolver with the riched Mock Functions API |
| Grouping        |         No         |                                                  Yes |

## Documentations

1. Puppeteer: https://pptr.dev
2. Jest: https://devhints.io/jest
3. Enzyme: https://enzymejs.github.io/enzyme/
