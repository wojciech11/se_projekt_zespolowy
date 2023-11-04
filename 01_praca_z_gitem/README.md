# Git workflows, working with git in teams

Powtórka podstaw - [instrukcja](https://github.com/wojciech11/se_software_build_automation_tools/blob/master/01_exercise/README_pl.md).

Git is not only a tool for storing the code but a powerful communication tool for teams!

## Best Practises

General:

- *master* / *main* /... - always working software!
- Continuous Deployment ASAP

## Demo 1:

My default workflow:

- short living branches with descriptive names,
- github flow (*one difference* when to deploy to prod),
- PR merge strategy: squash and merge,
- optional: early in draft (good for communication).
- **Mono repo first**

## Demo 2 - working with env:

Praca z różnymi środowiskami:

1. Local - na laptopie;
2. Dev - środowisko deweloperskie;
3. Staging / Pre-prod - prawie jak produkcja;
4. Prod.

Bonus: później można zainwestować w możliwość tworzenia, tymczasowych środowisk dla otwartych Pull Requests lub Merge Requests.

## Demo 3 - commit messages

- My default: imperative -> semantic (see below),
- [commit messages](https://github.com/wojciech11/se_software_build_automation_tools/blob/master/01_exercise/README_pl.md#zaawansowane---w%C5%82a%C5%9Bciwe-opisy-zmian).

## Tools

You should mainly use **git in the terminal** ([popular aliases](https://github.com/sorin-ionescu/prezto/tree/master/modules/git#branch-b)), still a visual tool helps a lot:

- [sourcetreeapp](https://www.sourcetreeapp.com) (my favorite);
- gitk/gitg;
- [vscode + GitLens](https://www.gitkraken.com/gitlens);
- [GitKraken](https://www.gitkraken.com) - wszystkie platformy.

## References

- https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
