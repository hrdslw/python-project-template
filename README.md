# python-project-template
Template for UNN python projects
## 1. Structure
### 1.1. Pyproject.toml - configuration file that stores project metadata, dependencies and tool settings in TOML format.
### 1.2. Package "project" that stores project's modules.
### 1.3. uv.lock - a file that locks in specific project settings, thereby ensuring consistent project behavior for everyone who has installed it.
## 2. Installation
### 2.1. Before installing this project, uv must be installed. Follow the link below to the developer's official website for installation instructions: https://docs.astral.sh/uv/getting-started/installation/
### 2.2. Project installation and synchronizing local device settings with the settings pinned in the uv.lock file
```
git clone https://github.com/mike-live/python-project-template.git 
cd python-project-template
uv sync
```