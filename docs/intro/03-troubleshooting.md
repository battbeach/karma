You are having some problems with the great Karma? Look no further.
Known problems and solutions are collected here so you don't have to figure them out again and again.
If you can't find any solution to your problem here, feel free to ask on the [mailing list].
Before complaining, please make sure you are on the latest version.
If you think you found a bug in Karma, please [submit an issue]. Please, make sure to search the existing issues first.

## Windows

### Tips & Tricks

* Use [chocolatey] for installation of tools. It helps. A lot.

### Specific problems

* Chrome won't start. (Issues: [#202], [#74])

  1. Set `CHROME_BIN` like this
     ```
     > export CHROME_BIN='C:\Program Files (x86)\Google\Chrome\Application\chrome.exe'
     ```

## Unix

### Tips & Tricks
In the event that your tests fail or freeze, this may be the result of
a browser having a display message show up, a browser update prompt or
extension-related conflict that needs to be taken care of.

[#202]: https://github.com/karma-runner/karma/issues/202
[#74]: https://github.com/karma-runner/karma/issues/74
[chocolatey]: http://chocolatey.org/
[mailing list]: https://groups.google.com/forum/#!forum/karma-users
[submit an issue]: https://github.com/karma-runner/karma/issues/new
