---
name: Custom issue template
about: My custom issue template
title: ''
labels: ''
assignees: ''

---

** As a ** Service Provider
** I need ** the service to be deployed to the Cloud
** So that ** I can scale capacity with user demand

### Details and Assumptions

- Artifacts for Cloud Faundry app have already been created in branch `cf-deploy`
- [ ] Database still needs to be provisioned
- [ ] App needs to be pushed and connected to the database

### Acceptance criteria

``` gherkin
Given I have deployed the cloud
When a customer comes to our URL
Then our service will be available
