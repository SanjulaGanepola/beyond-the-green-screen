🤖 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟴) - CI/CD with ibmi-ci and Source Orbit

Ever wish you could not only automate your builds on IBM i, but also gain detailed insight into what objects were impacted by your changes? Welcome to the future of CI/CD on IBM i with ibmi-ci and Source Orbit!

ibmi-ci is a CLI tool that can be used as part of any CI/CD pipeline (GitHub Actions, GitLab CI, Jenkins, Azure DevOps, etc.) to interact with your IBM i. You can use it to define a sequence of steps to execute, such as:
  • Running PASE or CL commands
  • Uploading directories to the IFS
  • Downloading artifacts
  • And much more!

The Source Orbit CLI tool can take this a step further by generating reports that give you visibility into:
  • Direct objects that were touched
  • Dependent objects that are impacted
  • Project-wide dependency relationships

In practice, here's how a team might leverage these tools together:

When a developer submits a pull request, ibmi-ci automatically builds the code into a sandbox library, and Source Orbit generates an impact report showing what was affected. This gives reviewers all the context they need to confidently approve changes — without the guesswork.

Follow for more #ibmi tips that go #BeyondTheGreenScreen