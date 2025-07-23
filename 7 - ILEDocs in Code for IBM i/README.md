📝 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟳) - ILEDocs in Code for IBM i

One of the great things about developing with Code for IBM i is that it follows the ILEDocs standard for writing documentation in the ILE languages. Using ILEDocs, you can add structured documentation blocks above procedures, variables, constants, and more. These blocks start and end with "///" and can include titles, descriptions, and tags like @param & @return.

Why does this matter? Well, Code for IBM i uses these comments to enhance features such as hover support, giving you rich, contextual information as you work—without needing to dig through code or separate documentation. Well-documented code not only helps your team understand what your procedures do, but also improves the overall development experience in modern editors.

My recommendation is to enforce this standard by enabling the "RequiresProcedureDescription" rule in your RPGLE lint configuration (rpglint.json). With this enabled, you'll get warnings when a procedure is missing a title or description. When you encounter one of these warnings, you can even quickly generate a documentation block template using the "Add title and description" code action.

Follow for more #ibmi tips that go #BeyondTheGreenScreen