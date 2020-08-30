## Procedure
### Mandatory steps
The following steps are required to merge the PR. Unless all the checks pass, it won't be merged:

- [ ] Create elinter branch in the repository and install recipe files using elinter.el.
- [ ] Add corresponding steps to the workflow file.
- [ ] If the project has a test suite, add it to the workflow as well.
- [ ] Linting and testing for the project passes.

### Optional steps
The following steps are not required to merge the PR but are recommended:

- [ ] If there is an existing Makefile for CI, rewrite it using elinter.
- [ ] If there is an existing GitHub Action, rewrite it using elinter.

## Feedback
Please check the following questions or leave comments:

- [ ] If there is an existing CI, does it produce the same result?
- [ ] If there is an existing CI, does elinter reduce the configuration?
