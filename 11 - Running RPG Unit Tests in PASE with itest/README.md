⚡️ 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟭𝟭) - Running RPG Unit Tests in PASE with itest

Remember back on Day 3, we introduced RPG unit testing in VS Code with the IBM i Testing extension? Today, we're build on that by showcasing how to run those exact same unit tests from the command line with the newly released IBM i Testing CLI.

This CLI gives developers the power to run unit tests outside VS Code — directly on IBM i or even locally on your PC. Just run the "itest" command with a few options to configure which tests to run, how to run them, and what reports to generate.

Now that we have a way to script the execution of our unit tests, the real magic happens in automation. With the release of this CLI tool, you can now automate test execution and generate code coverage reports as part of your CI/CD pipeline. Push a pull request, review your changes, and get immediate feedback on whether your code passes — just like you’d expect on any modern development stack. I’ll be sharing a full blog post soon with a deep dive on what CI/CD looks like for RPG developers working in Git using a combination of tools: ibmi-ci, Source Orbit, and now also the IBM i Testing CLI.

📥 Install: https://www.npmjs.com/package/@ibm/itest

Follow for more #ibmi tips that go #BeyondTheGreenScreen