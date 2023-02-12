# dotEnv tool

Description: Simple tool that help with generating .env files for development and/or production environments

Problem to solve: Sometimes on various projects/products there is an trouble of repetitive remaking .env file on multiple environments that are almost this same, usually you need to rewrite all of constant variable names that is sometimes waste of time and effectiveness, instead of rewriting this same dotEnv you could do something else.

Solution: This tool help you easily make an template of all of your dotEnv’s in project with great control over it that will shorten the time of struggling with environmental variables.

Goal: Simplify working with .env till the point of making template only once (or edit if needed) and creating .env whenever you need based on template.

Motto: “Make it one, use it multiple times”

Motivation: Making sharable templates for dotEnv’s across environments / projects / people / group / company. It should be easy and simple. Relatively easy extending for new functions. In every project .env shell be written only once not bazillion times once for each existing environment, also this tool should give an easy possibility for making standards and naming conventions across similar projects.

## Table of contents

- [dotEnv tool](#dotenv-tool)
  - [Table of contents](#table-of-contents)
  - [Features (Roadmap):](#features-roadmap)
  - [Languages that we support:](#languages-that-we-support)
    - [Main language of project (Rust)](#main-language-of-project-rust)
    - [So why you need python and JS?](#so-why-you-need-python-and-js)
  - [How to install](#how-to-install)
  - [How to use](#how-to-use)
  - [How to extend code by own solutions and standards](#how-to-extend-code-by-own-solutions-and-standards)
  - [Contribute to repository](#contribute-to-repository)
  - [Credits](#credits)
  - [License](#license)

## Features (Roadmap):

- [ ]  build .env:
    - [ ]  manually
    - [ ]  from template
- [ ]  generate .env easily using one of 3 modes:
    - [ ]  GUI - default
    - [ ]  CLI
    - [ ]  Browser Web page
- [ ]  create an .env template in:
    - [ ]  JSON
    - [ ]  XML
    - [ ]  YAML
- [ ]  multiple template files
- [ ]  clone template file
- [ ]  edit template files
- [ ]  create template from .env
- [ ]  export .env to global variables
- [ ]  variety of prefabricated variable types:
    - [ ]  Variable ← abstract class for variables, provide pools: “**field**”, “**required”** and  **“default**”, methods: toDotEnv(), build(), fill(), save()
    - [ ]  Simple ← simplest of all type, what you will write inside of him, will be write 1:1, it is threated as an text/string input
    - [ ]  Bool ← Boolean type variable is only true or false, will be threated as on/of switch, you can customize it to capitalize first letter or uppercase version
- [ ]  easy to extend by custom by variable because of inheritance
- [ ]  easy to extend for an new template format because of adapters used
- [ ]  easy to extend by new frontend because of adapters used
- [ ]  inheritance from other template
- [ ]  creating template form multiple parent template
- [ ]  ability to make stores on servers with docker that can handle all of your templates
- [ ]  prebuild templates

## Languages that we support:

- [ ]  Rust (executable file)
- [ ]  Python
- [ ]  Javascript (npm)

### Main language of project (Rust)

As an main language I choose rust. Why?

Relatively simple

Compliable

Can run everywhere after compilation

Starting to trending as an new C so it perspective there will be a lot of developers that will be able to handle any update of this project and grow it over time

Relatively easy to extern other languages with his functions

### So why you need python and JS?

Python is commonly used for scripting across DevOps (for example ansible)

Npm and other JavaScript technologies are once of most widespread once with a lot of solutions for frontend and backend, it is good to implement there this solution to.  

## How to install

To be done

## How to use

To be done

## How to extend code by own solutions and standards

To be done

## Contribute to repository

To be done

## Credits

Kacper Kotlewski * Self-clasping handshake *

## License

MIT license, do what you want :)