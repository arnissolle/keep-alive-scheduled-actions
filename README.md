[![Keep-Alive](https://github.com/arnissolle/keep-alive/actions/workflows/keepalive.yml/badge.svg)](https://github.com/arnissolle/keep-alive/actions/workflows/keepalive.yml)

# Keep alive your GitHub scheduled actions 📅 🕗 ✅

Maybe GitHub showed you a warning (as you can see on the image below) on one of your scheduled GitHub actions.

[IMAGE]

If so, let's consider implementing a Keep-Alive strategy. 

Take a look at the [keepalive.yml][1] action.

This scheduled action runs at 00:42 UTC on the 1st of every month.
A [.keepalive][2] file is added with the current date-time (human-readable) at the repository root and commits it.

Feel free to [report][3] any issues, and make pull requests to improve this
GitHub action.

[1]: https://github.com/arnissolle/keep-alive-scheduled-actions/blob/main/.github/workflows/keepalive.yml
[2]: https://github.com/arnissolle/keep-alive-scheduled-actions/blob/main/.keepalive
[3]: https://github.com/arnissolle/keep-alive-scheduled-actions/issues/new
