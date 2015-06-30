# Edit this Book

This book is produced using a hacked up [version](https://github.com/davidascher/gitbook/tree/webmaker-styling) of [Gitbook](https://github.com/GitbookIO/gitbook) (hacked so that the styling is more in line with build.webmaker.org).

To edit the content, just edit or create new markdown files in the [github repo](https://github.com/MozillaFoundation/book.webmaker.org/).  On git push to the `master` (default) branch, Travis will run a job and push the built HTML files to an S3 bucket that is pointed at by the `book.webmaker.org` domain.  Details of that job are in the [.travis.yml](https://github.com/MozillaFoundation/book.webmaker.org/blob/master/.travis.yml).

For through-the-web usage, you can either use the Github editor, or [prose.io](http://prose.io/#MozillaFoundation/book.webmaker.org)

This version of Gitbook only supports markdown files, but I believe you can have HTML embedded in markdown files.

Feedback [welcome](https://github.com/MozillaFoundation/book.webmaker.org/issues/).