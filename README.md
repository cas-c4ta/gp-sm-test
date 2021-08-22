# gp-sm-test
A GitHub Page test with submodules.

## Submodules

- [subpage 1 (p5-sm-test-1)](/p5-sm-test-1)
- [subpage 2 (p5-sm-test-2)](/p5-sm-test-2)

## Troubleshooting

Submodule mit ssh gibt Ärger mit Builds. Musste es nachträglich auf https ändern.

```
Your site is having problems building: The submodule registered for ./p5-sm-test-1 could not be cloned. Make sure it's using https:// and that it's a public repo. For more information, see https://docs.github.com/github/working-with-github-pages/troubleshooting-jekyll-build-errors-for-github-pages-sites#invalid-submodule.
```

[Origin von Sumbodules ändern](https://stackoverflow.com/questions/55241341/changing-https-address-of-submodules-in-git-config-to-ssh-address)

**Schritte unter obigem Link reichen nicht aus, bzw. sind irrelevant.**

Geändert werden muss die Datei `.gitmodules` im Hauptverzeichnis des Repos, siehe [Using submodules with GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/using-submodules-with-github-pages).
