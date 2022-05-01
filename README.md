# web-soft-workflows

Workflows files for Web-Soft projects.

# Usage

## Ci

Ci workflow run lint, test and optionaly build scripts for project.

**Requirements**

- Change TARGET_BRANCH to target pull requests branch/branches.
- Add secret NEED_BUILD to respository.

## Deploy

Deploy workflow build and publish image of current project to Docker Hub.

**Requirements**

- Change TARGET_BRANCH to target push branch/branches.
- Add secret DOCKER_HUB_USERNAME to respository.
- Add secret DOCKER_HUB_ACCESS_TOKEN to respository.
- Add secret DOCKER_HUB_IMAGE to respository.
