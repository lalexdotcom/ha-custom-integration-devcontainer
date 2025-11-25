# HA Custom Integration

[![Static Badge](https://img.shields.io/badge/HACS-default-orange?style=for-the-badge&logo=homeassistantcommunitystore&logoColor=white)](https://github.com/hacs/integration)
[![Static Badge](https://img.shields.io/badge/template-1.0.1--beta-blue?style=for-the-badge&logo=github)](https://github.com/lalexdotcom/ha-custom-integration-template/releases/tag/1.0.0-beta.1)



Start your [Home Assistant Custom Integration](https://developers.home-assistant.io/docs/creating_component_index/) for [Home Assistant Community Store (HACS)](https://hacs.xyz/) from a brand new test-ready and publish-ready project structure

## About
This repository template is just a VSCode devcontainer which gonna deploy a [cookiecutter](https://github.com/cookiecutter/cookiecutter) template based on the [integration_blueprint](https://github.com/ludeeus/integration_blueprint) bootstrap and inspired by [cookiecutter-homeassistant-custom-component](https://github.com/oncleben31/cookiecutter-homeassistant-custom-component).

## Prerequisites
This template is a devcontainer for VS Code. For more information, see the [VSCode docs](https://code.visualstudio.com/docs/devcontainers/containers)

## Installation
> [!WARNING]
> All files outside of the .devcontainer might be overwritten by the template (including this README)
> The default licence ifrom the template is MIT, consider updating the LICENSE file if you want a different licence

Fork this repository, then use it as a template for your new awesome custom integration (see [Github repository template doc](https://docs.github.com/fr/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template))
Then clone your newly created repository with VS Code, reopen it in container, answer to prompts and let the magic happen! :sparkles: :sparkles: :sparkles:

## Features
Every integration_blueprint features are here (Github Workflows, default structure), some of [cookiecutter-homeassistant-custom-component](https://github.com/oncleben31/cookiecutter-homeassistant-custom-component) also, and a bit more...
- Start from a brand new test-ready and production-ready folder structure
- Auto retrieval of github repository URL, project name and owner
- VSCode tasks to Run Home Assistant and Lint code
- Pre-filled class names
- README draft with HACS button link to my.home-assistant.io

For more infos and roadmap, please check the [template repository](https://github.com/lalexdotcom/ha-custom-integration-template)

## More infos
Please refer to the [HACS publish page](https://www.hacs.xyz/docs/publish/integration/) to match the required specifications before publish (basically, you just have to handle the (https://github.com/home-assistant/brands) part)...