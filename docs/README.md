# Jest/React Testing Library Tests
## WORK IN PROGRESS
![Jester juggling React logos.](./jest-react.png "Jester juggling React logos.")

This project demonstrates my ability to write effective tests against a pre-existing application using Jest and the newly released [React Testing Library](https://github.com/kentcdodds/react-testing-library) from Kent C. Dodds. I originally submitted an earlier version of this project for the Udacity Front-End Developer Nanodegree program. That version used Jasmine and can be viewed [here](https://github.com/chocobuckle/jasmine-bdd), but it's 2018 now, folks - so I updated the project to use Jest and React Testing Library. Why not JEst and Enzyme? Coz it's April 2018, not March! #javascriptfatigue

While you're here, let me hop up on my soapbox for a sec... I believe that if you're using static types with TypeScript/Flow, using Prettier and TSLint/ESLint, and writing declarative code, then there's little point in developers writing unit tests anymore. Instead, I think the only tests developers with modern tools should be writing 95% of the time are integration tests, regression tests using Jest's awesome snapshot feature, and end-to-end tests. But mostly integration tests! If you're writing unit tests for a React application, say, then you're very likely just testing React, not your actual application. It's a mistake I regularly see many online tutorials still making, resulting in developers spending countless hours writing umpteen lines of unncessary code. Kent C. Dodds [explains all this](https://blog.kentcdodds.com/write-tests-not-too-many-mostly-integration-5e8c7fff591c) far better than I can though!



