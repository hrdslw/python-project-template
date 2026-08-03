[[!CI workflow](https://github.com/mike-live/python-project-template/actions/workflows/CI.yml/badge.svg)](https://github.com/mike-live/python-project-template/actions/workflows/CI.yml)

# python-project-template
Template for UNN python projects
## 1. Structure
  * Pyproject.toml - configuration file that stores project metadata, dependencies and tool settings in TOML format. 
  * Package "project" that stores project's modules.
  * uv.lock - a file that locks in specific project settings, thereby ensuring consistent project behavior for everyone who has installed it.
## 2. Installation
  * Before installing this project, uv must be installed. Follow the link below to the developer's official website for installation instructions: https://docs.astral.sh/uv/getting-started/installation/
  * Project installation and synchronizing local device settings with the settings pinned in the uv.lock file
```
git clone https://github.com/mike-live/python-project-template.git 
cd python-project-template
uv sync
```