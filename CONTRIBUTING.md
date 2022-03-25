# Contributing

The [Code of Conduct](CODE_OF_CONDUCT.md) applies to all contributions (PRs, issues, comments, etc). Thanks!

## Workflow

1. Fork the project.
2. It's up to you whether you'd like to work on your fork's `main` or a feature branch. The latter would probably be more useful if you're submitting an idea that has more in-depth guidelines.
3. One idea = one commit, please. Write commit messages in the present imperative tense, so that they read as changes to be applied to the repo rather than a diary of changes made ("Add the widget" would be correct, vs. "Added the widget").
4. Submit a PR to the `main` branch!

### Branch name changes

The default branch for this project was renamed from `master` to `main`. If you have a fork with the old branch name, you can update your local clone with the following commands:

```
$ git checkout master
$ git branch -m master main
$ git fetch
$ git branch --unset-upstream
$ git branch -u origin/main
$ git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main
```

## Formatting

* Follow [this style](https://guides.github.com/features/mastering-markdown/) of Markdown. We're using asterisks instead of dashes for bulleted lists.
* If you add an idea to the list:
  * Follow the same imperative grammatical structure: "Do a thing", instead of "A thing"
  * If your idea has more in-depth guidelines than a simple sentence, format your idea in the list as `Do a thing ([Guidelines](docs/your-idea.md))`. As shown in this example, the word "Guidelines" links to a markdown file in the `docs/` folder detailing your project idea's guidelines.