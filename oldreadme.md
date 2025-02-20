# MaRDA's Very Own Awesome List

This is a public Awesome List of MaRDA related things.  It has
CI to run [awesome-lint](https://github.com/sindresorhus/awesome-lint) and
[awesome_bot](https://github.com/dkhamsing/awesome_bot) to be compliant from the
beginning.

## Contributing

Contributions welcome! Make an PR and put your resources in a branch.  Someone will review and merge.  We don't really know the process, yet because we just made it during the break on the last day of MaRDA2025 but we'll work it out!

ToDo: 
4. choose a CI template
   - GitHub Action: move config folder from `repo-root/ci/.github/` to
     `repo-root/.github`
   - Circle CI: move config folder from `repo-root/ci/.circleci/*` to
     `repo-root/.circleci/*`
   - GitLab CI: move config file from `repo-root/ci/.gitlab-ci.yml` to the
     `repo-root/.gitlab-ci.yml`
5. run a find & replace `readme-template.md` to `readme.md` in the CI you chose
