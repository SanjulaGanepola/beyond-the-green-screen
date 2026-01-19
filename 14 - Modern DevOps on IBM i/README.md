⏳ 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟭𝟰) - Modern DevOps on IBM i

Ever wish you could not only automate your builds on IBM i, but also gain detailed insight into what objects were impacted by your changes and run unit tests? Well, now you can with a modern CI/CD pipeline on IBM i using ibmi-ci, Source Orbit, and itest.

  • 𝗶𝗯𝗺𝗶-𝗰𝗶: A CLI tool to interact with your IBM i by executing a defined sequence of steps. This can include running PASE or CL commands, uploading directories to the IFS, downloading artifacts, and more.
  • 𝗦𝗼𝘂𝗿𝗰𝗲 𝗢𝗿𝗯𝗶𝘁: A CLI tool to generate impact analysis reports that give insight into direct objects that were touched, dependent objects that are impacted, and project-wide dependency relationships.
  • 𝗶𝘁𝗲𝘀𝘁: A CLI tool to run RPGUnit test suites and generate code coverage reports.

In practice, here's how a team might leverage these tools together:

When a developer submits a pull request, ibmi-ci builds the code into a sandbox library, Source Orbit generates an impact report showing what was affected, and itest runs all your unit tests with code coverage. This gives reviewers all the context they need to confidently approve code changes.

Follow for more #ibmi tips that go #BeyondTheGreenScreen