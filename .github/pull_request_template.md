Find the pull request instructions [here](pull_request_template.md)

Every reviewer and the owner of the PR should consider these points in their request (feel free to copy this checklist so you can fill it out yourself in the overall PR comment)

- [ ] The code is extensible and backward compatible
- [ ] New public interfaces are extensible and open to backward compatibility in the future
- [ ] If preparing to remove a field in the future (i.e. this PR removes an argument), the argument stays but is no longer functional, and attaches a deprecation warning. A linear task is also created to track this deletion task.
- [ ] Non-critical or potentially modifiable arguments are optional
- [ ] Breaking changes and the approach to handling them have been verified with the team (in the Linear task, design doc, or PR itself)
- [ ] The code is easy to read
- [ ] Unit tests are added for expected and edge cases
- [ ] Integration tests are added for expected and edge cases
- [ ] Functions and classes are documented
- [ ] Migrations for both up and down operations are completed
- [ ] A documentation PR is created and being reviewed for anything in this PR that requires knowledge to use
- [ ] Implications on other dependent code (i.e. sample games and sample bots) is considered, mentioned, and properly handled
- [ ] Style changes and other non-blocking changes are marked as non-blocking from reviewers
