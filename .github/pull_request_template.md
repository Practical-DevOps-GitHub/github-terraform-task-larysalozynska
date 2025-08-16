## Describe your changes

## Issue ticket number and link

## Checklist before requesting a review
- [ ] I have performed a self-review of my code
- [ ] If it is a core feature, I have added thorough tests
- [ ] Do we need to implement analytics?
- [ ] Will this be part of a product update? If yes, please write one phrase about this update

5. A deploy key named `DEPLOY_KEY` should be added to the repository.

6. Create a Discord server and enable notifications when a pull request is created.

7. For GitHub actions, perform the following:
- create PAT (Personal Access Token) with **Full control of private repositories** and **Full control of orgs and teams, read and write org projects**
- add the PAT to the repository actions secrets key with the name `PAT` and the value of the created PAT.
