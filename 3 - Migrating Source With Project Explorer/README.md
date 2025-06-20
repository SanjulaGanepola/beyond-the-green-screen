🚚 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟯) - Migrating Source With Project Explorer

One of the first steps toward modern development with Git on IBM i is migrating your source out of QSYS and into a Git repository. Fortunately, Project Explorer makes this process simple with an intuitive UI.

Behind the scenes, it uses the "cvtsrcpf" utility from Bob to migrate your source to the IFS. Once that is done, Project Explorer automatically pulls the source down to your local machine—ready for local development. If you have Source Orbit installed, the process gets even smoother. It can automatically update your copy/include directives to use Unix-style paths and adjust file extensions to match what common build tools expect.

Follow for more #ibmi tips that go #BeyondTheGreenScreen