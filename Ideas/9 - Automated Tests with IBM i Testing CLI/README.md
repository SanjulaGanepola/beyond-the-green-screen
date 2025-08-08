🎯 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟵) - Automated Tests with IBM i Testing CLI

Remember back on Day 3, we introduced RPG unit testing in VS Code with the IBM i Testing extension and on Day 7, we explored automated builds with ibmi-ci? Today, we bring it all together with the newly released IBM i Testing CLI.

This CLI gives developers the power to run unit tests outside VS Code — from a local terminal or directly on IBM i in the IFS or a library. Just run the "itest" command with a few options to configure which tests to run, how to run them, and what reports to generate.

Now that we have a way to script the execution of our unit tests, the real magic happens in automation. By running "itest" as part of your ibmi-ci command, you can automate test execution and generate code coverage reports as part of your CI/CD pipeline. Push a PR, review your changes, and get immediate feedback on whether your code passes — just like you’d expect on any modern development stack.

The end-to-end development experience on IBM i continues to evolve rapidly, and the IBM i Testing CLI is a key part of that journey — helping developers ensure code quality and reliability every step of the way.

⚡ Install: https://www.npmjs.com/package/@ibm/ibmi-testing
📖 Documentation: https://codefori.github.io/docs/developing/testing/overview/

Follow for more #ibmi tips that go #BeyondTheGreenScreen