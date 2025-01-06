# Get
Download the installer from the [Releases page](https://github.com/endre-git/aoget/releases). The latest version is **0.9.1**. Happy downloading!

# What's this?
AOGet is a download manager for easy fileset downloads from archive.org, or any other website that provides directory listing - a collection of downloadable URLs on a single page. It has a qBittorrent/uTorrent-like user interface for easy user adoption.
[User Guide](https://github.com/endre-git/aoget/wiki/User-Guide) is here.

## Single GIF manual
![Single GIF manual](aoget/docs/aoget_manual.gif)

## Limitations, known issues
* The app is the result of a laerning exercise (Python) and is beta. Expect issues.
* It was written in Python and can be a little slow with large filesets.
* It does not support parallel download threads for a single file, but can download many files in parallel.
* Job deletion is slow with large jobs.
* You can set global bandwidth limits, but not on a per-file basis.
* The app does not explore directories recursively, it's limited to the flat set of files on a page.
* There is no support for page logins, CAPTCHAs or any other non-trivial downloads.
* As of 0.9.1 the rate display will be unreliable with very slow servers (<4KB/s) or many threads + bandwidth limit.
* The target filenames are not temporaray as is the good practice with download managers (.filepart etc.)

## What's next?
I might do updates if anybody needs them.
* [v0.9.2 Milestone](https://github.com/endre-git/aoget/milestone/11) is a 60/40% bugfix/feature release with minor enhancements.
* [v1.0 Milestone](https://github.com/endre-git/aoget/milestone/6) is about additional enhancements.
* [Later](https://github.com/endre-git/aoget/milestone/9) are nice-to-haves.

# Contribute
## Give feedback
Please use the [Discussions](https://github.com/endre-git/aoget/discussions/) tab.

## Report bugs
When the app crashes, it'll prompt you to open a new issue. If you have a GitHub account, or willing to create one, please report issues. If you want to go the extra mile, you can check in the [existing set of issues](https://github.com/endre-git/aoget/issues/) whether your case was reported already.

## Develop
You can actively develop AOGet. Take a look at the [issues](https://github.com/endre-git/aoget/issues/), fix one, raise a PR and bug me to get it reviewed and merged. Consult the [wiki](https://github.com/endre-git/aoget/wiki/) on how to get started.


