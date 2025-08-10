# Exercise 11.1

For this scenario, I will assume our application is written in JavaScript. In a typical CI (Continuous Integration) pipeline for JavaScript, the first step is linting, which ensures code style consistency and detects common issues early. A widely used tool for this is ESLint, which is highly configurable and supports many plugins for different coding standards.

The second step is testing. Popular JavaScript testing frameworks include Jest and Mocha. Jest is particularly popular for its built-in assertion library, snapshot testing, and zero-configuration setup for many projects. Mocha, combined with assertion libraries like Chai, offers more flexibility for complex setups.

The third step is building. In a Node.js backend project, this may involve transpiling modern JavaScript (or TypeScript) using Babel or compiling and bundling assets for frontend parts using Webpack, Rollup, or Vite. For purely backend services, the build step might simply ensure dependencies are installed and code is production-ready.

Beyond Jenkins and GitHub Actions, there are several alternatives for CI, such as GitLab CI/CD, CircleCI, Travis CI, and Azure Pipelines. These platforms differ in cost, integration capabilities, and ease of use.

The decision between a self-hosted or cloud-based CI depends on security requirements, infrastructure constraints, and maintenance capacity. Self-hosted CI allows greater control and customization, which can be crucial for organizations with strict compliance rules. Cloud-based CI services offer ease of setup, automatic scaling, and reduced operational overhead. To choose, I would need to know the project’s security policies, expected build volume, team DevOps expertise, and budget.
