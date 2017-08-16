# W3C Web of Things Working Group

https://www.w3.org/WoT/WG/

## Specifications

GitHub repositories are linked from each specification:

* https://w3c.github.io/wot-architecture/
* https://w3c.github.io/wot-thing-description/
* https://w3c.github.io/wot-scripting-api/
* https://w3c.github.io/wot-binding-templates/

Web of Things tests are to be added to [web-platforms-tests][WPT].

## Repositories

* https://github.com/w3c/wot-architecture/
* https://github.com/w3c/wot-thing-description
* https://github.com/w3c/wot-scripting-api
* https://github.com/w3c/wot-binding-templates

## Contributing

Editorial changes that improve the readability of the spec or correct spelling or grammatical mistakes are welcome, and may be done directly from the web interface of github.
However, in general changes should be done by pull requests. Please follow the following guidelines for the contribution workflow:
- Fork the repository, then clone the fork.
- Create a local branch in your fork, push commits there, then make a pull request. After the pull request is merged, the local branch can be optionally deleted.
- Sign the commits (use e.g. `git commit -s -m "message"`).
- Make commit messages specific and informative, e.g. by including issue numbers.
- For bigger commits, the first line of the commit message should be a short summary, then after an empty line a more detailed description or rationale of the commit should follow.
- Similarly, pull request comments should follow the same principles as commit messages.
- For HTML files please provide a link to a rendered diff in the pull request, using the [W3C HTML diff tool](https://services.w3.org/htmldiff) for comparing two versions of the same file from different forks and branches. See an example [here](https://services.w3.org/htmldiff?doc1=https%3A%2F%2Fw3c.github.io%2Fwot-scripting-api%2F&doc2=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielpeintner%2Fwot-scripting-api%2Fmaster%2Findex.html).
Note that the tool expects the "raw" link to the files, for instance this file's raw link is [https://github.com/w3c/wotwg/raw/master/README.md](https://github.com/w3c/wotwg/raw/master/README.md) that resolves to [https://raw.githubusercontent.com/w3c/wotwg/master/README.md](https://raw.githubusercontent.com/w3c/wotwg/master/README.md), and can be obtained by clicking on the `Raw` button when the file is displayed on the github web page.)
- Pull requests should be reviewed and approved by someone else (typically an editor), then approved and merged by an editor or chair.
- The preferred way to merge a pull request is by creating a merge commit, or by squashing (select the option from the pull-down menu right to the merge button). To keep full history, rebase merge is fine if commits are well defined and formatted.

Please read [CONTRIBUTING.md](CONTRIBUTING.md), about licensing contributions.

## History

See the [WoT IG repository](https://github.com/w3c/wot).

[WPT]: https://github.com/w3c/web-platform-tests/
[db]: https://www.w3.org/WoT/WG/wiki/ (TBD)
