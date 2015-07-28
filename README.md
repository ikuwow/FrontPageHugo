# Technology Media Lab Portal Site

## Before build

Install hugo and mecurial by homebrew,

```bash
$ brew intsall hugo hg
```

and clone repository forked to your account.

```bash
$ git clone git@github.com:myaccount/FrontPageHugo.git
```

## How to develop

Run build-in server.

```bash
$ hugo server --watch
[...]
Watching for changes in /Users/ikuo.degawa/workspace/FrontPageHugo/{content,layouts,static}
Serving pages from /Users/ikuo.degawa/workspace/FrontPageHugo/public
Web Server is available at http://127.0.0.1:1313/
Press Ctrl+C to stop

```

`--watch` enables hugo watching file changes and auto reloading.

And type `http://127.0.0.1:1313/` in your web browser.

That's it. Happy Coding.


