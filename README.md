Service-Level Agreement
=======================

This service-level agreement (SLA) describes the level of support that you should expect.

Uptime
------

-	**95%+ uptime**

	The packages build successfully, and have their tests pass at least 95% of the time in a year.

Response Time
-------------

-	**unspecified response time**

	Issues, pull requests and comments are responded to with no timing guarantees.

Breaking API Changes
--------------------

-	**No backwards compatibility**

	There are no hard backwards compatibility guarantees, but I try to update all affected code when I break an API. If you import my packages and I know of that via godoc.org importers, I will send a PR to update your package.

	See [bradfitz/go-issue-mirror#5](https://github.com/bradfitz/go-issue-mirror/pull/5), [bradfitz/go-issue-mirror#6](https://github.com/bradfitz/go-issue-mirror/pull/6), and [bradfitz/go-issue-mirror#16](https://github.com/bradfitz/go-issue-mirror/pull/16) as some recent examples of that.

	If you vendor my packages, it's your own responsibility to update when you want to.

-	**Forward progress**

	Because there's no backwards compatibility promise, it's always okay to change things to make things better. Even if an API is not 100% optimal in the first commit, it's not frozen and can be improved later.

Go Version
----------

-	**Current stable Go version**

	Current stable Go version is supported. Previous versions may work, but aren't guaranteed to. I don't go out of my way to break support for previous versions, but I don't hold back on using new features from current stable Go version.

Applicability
-------------

This SLA applies to all Go packages under the following namespaces:

-	[`dmitri.shuralyov.com/...`](https://dmitri.shuralyov.com/...)
-	[`github.com/shurcooL/...`](https://github.com/shurcooL?tab=repositories)
-	[`github.com/goxjs/...`](https://github.com/goxjs?tab=repositories)

with the exception of:

-	`github.com/shurcooL/play/...`
