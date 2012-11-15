QMachine
=========

[QMachine](https://qmachine.org) is a web service that uses
[Quanah](http://wilkinson.github.com/quanah) to act as a "supercomputer" that
distributes computations across web browsers using only
[Node.js](http://nodejs.org) and [Apache CouchDB](http://couchdb.apache.org/).
My only reason for using Node.js is the lack of support for
[CORS](http://www.w3.org/TR/cors/) in CouchDB, which is otherwise completely
sufficient by itself to implement the QMachine API; the silver lining here,
however, is that the CORS-enabled proxy I wrote with Node.js can then be bound
to other databases like [MongoDB](http://www.mongodb.org/),
[PostgreSQL](http://www.postgresql.org), and [SQLite](http://www.sqlite.org).
Keep in mind that the bindings for databases other than CouchDB are still
experimental! Also, because I am currently writing several academic papers
about Quanah and QMachine, the Node.js client has fallen out of date.

As in all my projects, the best documentation is contained inline as comments
within the source code. I have written some tutorials recently, but those are
very low priority until the papers are completed.

There are several "mirrors" available on
[Bitbucket](https://bitbucket.org/wilkinson/qmachine),
[GitHub](https://github.com/wilkinson/qmachine), and
[Google Code](https://qmachine.googlecode.com).

A Node.js module can be installed via [NPM](https://npmjs.org/package/qm).

I have done some preliminary investigation into app integration for

-   [Google Chrome](https://chrome.google.com/webstore/detail/meagomakeegjimdibmlodmilfhplkjgp?utm_source=chrome-ntp-icon)
-   [Facebook](http://apps.facebook.com/qmachine/)
-   [Twitter](https://dev.twitter.com/apps/1755018/)

In the future, I would like to integrate QMachine with "app ecosystems" like

-   [Android](https://play.google.com/store/apps)
-   [App.net](https://github.com/appdotnet/api-spec/wiki/Developer-Wiki)
-   [BlackBerry](http://us.blackberry.com/apps-software/appworld/)
-   [CloudFlare](https://www.cloudflare.com/apps/)
-   [DirecTV](http://tvapps.directv.com/)
-   [Dropbox](https://www.dropbox.com/developers/apps/)
-   [ePrintCenter](https://h30495.www3.hp.com/apps/)
-   [Google Apps Marketplace](https://www.google.com/enterprise/marketplace/)
-   [Heroku](https://addons.heroku.com/)
-   [Internet Explorer Gallery](http://www.iegallery.com/)
-   [Kynetx](http://developer.kynetx.com/)
-   [Mozilla Marketplace](https://www.mozilla.org/en-US/apps/partners/)
-   [iOS](http://itunes.apple.com/us/app/)
-   [Podio](https://podio.com/store)
-   [Samsung](http://www.samsungapps.com/)
-   [SMART Platform](http://www.smartplatforms.org/)
-   [Windows Phone](http://www.windowsphone.com/en-US/marketplace)
-   [Yahoo! Connected TV](http://connectedtv.yahoo.com/developer/tvstore/)

