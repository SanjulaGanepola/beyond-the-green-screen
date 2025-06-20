🕵🏻‍♂️ 𝗕𝗲𝘆𝗼𝗻𝗱 𝘁𝗵𝗲 𝗚𝗿𝗲𝗲𝗻 𝗦𝗰𝗿𝗲𝗲𝗻 (𝗗𝗮𝘆 𝟳) - Diagnosing Issues in Code for IBM i

If you have ever submitted a bug report to the Code for IBM i team, you will know that we often ask for the full extension log to help diagnose what went wrong. There are two simple ways to get it:
  • Copy it directly from the "Code for IBM i" output channel
  • Use the "Download Logs" option in the "Help and Support" view

But here is the real tip: you can often diagnose the issue yourself just by checking this log!

Whenever Code for IBM i runs any command, it logs everything—the command itself, the return code, and both the standard output and standard error. So the next time something doesn’t work as expected, scroll through the log, find the command that was run, and take a look at the messages. You might be surprised how often you can quickly spot the issue yourself and get issues resolved faster.

Follow for more #ibmi tips that go #BeyondTheGreenScreen