# GitHub Action Reusable Workflows

Required GitHub Action Reusable Workflows for Devilbox. See [.github/workflows](.github/workflows) and [.github/actions](.github/actions).


## :computer: Usage

See how the reusable workflows are used [from this repository](https://github.com/john-ea/devilbox-actions/network/dependents).


## :exclamation: Keep up-to-date with GitHub Dependabot


Since [Dependabot](https://docs.github.com/en/github/administering-a-repository/keeping-your-actions-up-to-date-with-github-dependabot) has [native GitHub Actions support](https://docs.github.com/en/github/administering-a-repository/configuration-options-for-dependency-updates#package-ecosystem), to enable it on your GitHub repo all you need to do is add the `.github/dependabot.yml` file:

```yml
version: 2
updates:
  # Maintain dependencies for GitHub Actions
  - package-ecosystem: "github-actions"
    directory: "/"
    schedule:
      interval: "daily"
```

Then Dependabot will PR you version updates as soon as this repository gets updated.


## :page_facing_up: License

**[MIT License](LICENSE)**

Thanks to [cytopia](https://github.com/cytopia) and the [devilbox](https://github.com/devilbox) project. 
