# Links for Github Actions Presentation Linux Usergroup Nijmegen


* Using my Raspberry Pi to run an existing GitHub Action https://blog.frankel.ch/raspberry-pi-github-action/

Tools used in demos

* yamllint: https://github.com/adrienverge/yamllint
* twilio: https://www.twilio.com/

---

# Notes

- CI/CD:
    - From Extreme Programming XP, 1991
    - Nowadays mostly about automation
    - CI - Continuous integration
    - CD - Continuous deployment or delivery

    - CI/CD has one important leg: workflows and their automation

- Github Actions
    - Automates workflows
    - Is therefore often called "CI server"
    - GitLab made that even worse: they do as if CI == GitLab

    - Common Github Actions workflows
       - Linting
       - Automated tests
       - Builds and releases
       - Documentation extraction
       - Deployment

    - But also
       - Notification
       - CMS/static site building
       - Cron: daily/hourly tasks
       - Security scans
       - Automate tickets
       - Integrate with 3rd party services
       - Sync
       - Shields

- Actions Concepts
    - Workflow
    - Jobs
    - Steps

    - Secrets
    - Conditionals
    - Dependencies
