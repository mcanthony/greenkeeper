# Getting Started with Greenkeeper

[![Build Status](https://travis-ci.org/greenkeeperio/greenkeeper.svg?branch=master)](https://travis-ci.org/greenkeeperio/greenkeeper)
[![Dependency Status](https://david-dm.org/greenkeeperio/greenkeeper/master.svg)](https://david-dm.org/greenkeeperio/greenkeeper/master)
[![devDependency Status](https://david-dm.org/greenkeeperio/greenkeeper/master/dev-status.svg)](https://david-dm.org/greenkeeperio/greenkeeper/master#info=devDependencies)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

[![NPM](https://nodei.co/npm/greenkeeper.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/greenkeeper/)

To install Greenkeeper, type:

    $ npm install -g greenkeeper

Then log in:

    $ greenkeeper login

Your browser will open a new window or tab and redirect you to
GitHub’s Application Authentication screen. There is a big green
button [Authorize application] at the bottom. When you click it,
Greenkeeper gets the access to GitHub it needs to do its job, but
no more. When all goes well, your browser will say “Check your
Terminal”, and when you switch back here, the login will be done
and Greenkeeper will have started to sync your GitHub repo
information.

Congratulations, you made it past the most complicated step!

Next, you enable a package of yours. To do this, navigate to a
local copy of your package (e.g. `cd ~/code/mypackage`). Then:

    $ greenkeeper enable

And that’s it already! :)

From here on out, Greenkeeper will do its job automatically. If your
dependencies are already outdated the first thing you are going to
notice is a Pull Request where we update all your dependencies in
your package’s package.json to their respective latest versions.
Then, whenever one of your dependencies is updated on npm, you will
receive a Pull Request to update your package accordingly.

If you’d like to talk to a human or want to report an issue, type:

    $ greenkeeper support

🌴
