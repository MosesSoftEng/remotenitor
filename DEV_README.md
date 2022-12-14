# :book: Remonitor Project.

Remonitor is a service to allow an admin to monitor multiple groups of devices (examples: employees, students and children). The service enables the admin to get user's device usage stats, login logout times and screenshots of the device screen at set intervals for monitioring.

## Project setup

### Environments
 - Development environment - dev branch
 - Staging environment - stage branch
 - Production environment - git pull branch

### Create repos
```bash
# Create stage and Dev branches.
git branch stage 
git branch dev

git branch -a

git checkout dev

# Add admin front end submodule
git submodule add -f  https://github.com/MosesSoftEng/remonitor-admin-front.git

# Add aws backend submodule
git submodule add -f  https://github.com/MosesSoftEng/remonitor-backend-aws.git

# Add desktop submodule
git submodule add -f https://github.com/MosesSoftEng/remonitor-client-desktop.git

```

# :man: Author and Credits.
This project was done by [SE. Moses Mwangi](https://github.com/MosesSoftEng). Feel free to get intouch with me;

:iphone: WhatsApp [+254115227963](https://wa.me/254115227963)
