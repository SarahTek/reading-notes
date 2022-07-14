# Read class 02

## Readings: Express, NPM, TDD, CI/CD

### An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

- Middleware is software that lies between an operating system and the applications running on it.It acts like the connective tissue between applications, data, and users. 

2. Express the most popular Node Web Framework.

3. Express is “unopinionated.” What does that mean?

- It means there is no one right way to do things that Express will force you into.

4. What is a module and why is modularity useful to us as developers?

- A module  is just a file containing related code. modularizing is subsidizing a prewritten code into a smaller modules.

What is NPM?

1. What version of npm are you running on your machine?

- 8.12.1

2. What command would you type to install a library/package called ‘jshint’ into your node project?

- npm install jshint 

What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.

- devs write test codes to make sure that the code works correctly.

2. What are three expected benefits of testing?

- Better program design and higher code quality
- code flexibility and easier maintenance
- detailed project documentation

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- forgetting to run tests frequently
- writing tests that are too large 

CI/CD

1. What are three benefits of Continuous Integration?

- Continuous integration (CI) makes software development easier, faster, and less risky for developers. By automating builds and tests, developers can make smaller changes and commit them with confidence. Developers get feedback on their code sooner, increasing the overall pace of innovation.

2. What is the difference between Continuos Delivery and Continuous Deployment?

- countinuous delivery (CD) is the practice of developing software in such a way that you could release it at any time. A state where your application is always ready to be deployed. A manual step is required to actually deploy the application.

- Continuous Deployement is the automation of building, testing, and deploying. If all tests pass, every new commit will push new code through the entire development pipeline to production with no manual intervention.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

- github is like a clearing house for your code. developers make changes to their code locally and  push those changes to GitHub to share them with others. We use CI/CD methods to automate, test and deploy those changes. 

### Resources
- [TDD](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
- [Node.js and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
- [NPM](https://docs.npmjs.com/about-npm)
- [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)
