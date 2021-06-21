**What is a pull request for**  
Please check the type of request, label them according to the type of pull request that applies.
- If type of pull request is :
  - **Update Documentation**, add  `documentation` label
  - **Update environment**, add `environment` label
  - **Add feature**, add `feature` label
  - **Fix bug**, add `bug` label
  - **Re-factory source**, add `re-factory` label
  - **Update repository**, add `repository` label
  - **Etc**, add `etc` label

**Related issues**  
Write about related issues. To close a related issue, write it in the `Status`. If you want see explanation of keywords for closing issues, Reference to here : [Linking a pull request to an issue using a keyword](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword)

- [close keyword] [issue number]
- [close keyword] [issue number]

**Description of requested changes**
For details on how to write a pull request, refer to the [Contribution Guide](../blob/master/CONTRIBUTING.md#how-to-create-pull-request).

Changed :
   - Add README.md in repository
   - Update content Item in README.md
   - Refactory source for login method
   - Rename README.md to readme.md
   - Fix login error
   - Delete README.md

**Checklist self-code review**
- [ ] Code is self-documenting and easy to understand
- [ ] Tests are present (preferably not only snapshots)
- [ ] There is no commented out code
- [ ] Errors or exceptions are handled
- [ ] Naming of methods, variables, and classes is proper
- [ ] There is no unnecessary logging or debugging code
- [ ] Changes are documented in CHANGED.md(if necessary)
      
**Checklist before pull request**
- [ ] I checked contributing guide
- [ ] I performed a self-review of my own code (and followed code review checklist)
- [ ] I set proper `type of pull request` label
- [ ] I wrote unit and/or integration tests
- [ ] I wrote a description of requested changes
- [ ] I wrote a description of change file list by pull request
