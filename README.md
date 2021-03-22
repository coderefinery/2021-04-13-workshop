# CodeRefinery workshop webpage

This repository is a template to set up webpages for CodeRefinery
workshops, and has coordination of roles.



## Quick reference
- [Helper availability overview and exercise plan](https://docs.google.com/spreadsheets/d/1NeIRs7c8br0xjcxxETNd__19JtfEERe-KFd9JUjP0wU/edit#gid=0)



## Role coordination

You should *edit directly on the default branch* when signing up for a
role.  Signing up for multiple roles, or splitting them, is
encouraged.  Opt for efficiency over re-inventing things.

General roles:

- [ ] **[Event lead](https://coderefinery.github.io/manuals/workshop-administration/):**
- [ ] **Registration/communication:**
- [ ] **Dissemination:**
- [ ] **Teaching coordinator:**
- [ ] **Helper coordinator:**
- [ ] **HackMD preparation:** (default: hackmd of that day)
- [ ] **Breakout rooms preparation:** (default: host)


Workshop preparation:

- [ ] **(DD.MM) Installation help 1:**
- [ ] **(DD.MM) Installation help 2:**
- [ ] **(DD.MM) Helper training 1:**
- [ ] **(DD.MM) Helper training 2:**


During workshop:

- **Instructors** sign up on the schedule page.
- [ ] **Host:**
- [ ] **Communication with attendees:**
- [ ] **HackMD:**
  - [ ] Day 1:
  - [ ] Day 2:
  - [ ] Day 3:
  - [ ] Day 4:
  - [ ] Day 5:
  - [ ] Day 6:
- **Expert helpers:**
  - [ ] Day 1:
  - [ ] Day 2:
  - [ ] Day 3:
  - [ ] Day 4:
  - [ ] Day 5:
  - [ ] Day 6:
- [ ] **Production tech:**
- **Exercise leaders** are coordinated separately (via registration form)

After the workshop:

- [ ] **Post HackMD:** (default: HackMD helper of that day)
- [ ] **Send out survey:** (default: handled as part of another batch process)



## How to generate your workshop repository

To use it, follow these instructions:
- Click the green "Use this template" button.
- Select owner of the new repository and repository name. The name should be
  "year-month-date-place", e.g. `2019-10-16-stockholm` or `2019-10-16-online`.
- Click "Create repository from template".
- You will now be redirected to the new repository.
- [x] test
- [ ] test2

### How to customize this template after you have created the repository

- Adapt `config.toml`:
  - adapt `base_url` (it should contain a trailing slash)
  - adapt `title`
  - adapt settings below `[extra]`
- Adapt schedule in `content/_index.md`


### How this template works

This template is based on the [Zola](https://www.getzola.org/) static site engine.

To install Zola, follow:
- https://www.getzola.org/documentation/getting-started/installation/
- https://snapcraft.io/zola can be used for system that are not supported by default
- But you can also download the binary directly from [here](https://github.com/getzola/zola/releases)

Check that Zola is installed with `$ zola --version`.


#### Local preview

```
$ zola serve --open
```
This will open in your default browser a rendered version of the template.
