Cohaesus Labs Standards
=======================
> This repository and document outline expected standards and conventions and provide boilerplate templates for all Cohaesus Labs projects.

## Repository/Project Naming
From this point forth, all projects must adhere to the naming convention agreed by all staff, each project should be named after an famous computer of some description - this can be a fictional (e.g. from a film) computer, or the name of a specific model. Some [examples are available here](http://namingschemes.com/Psychotic_Computers)

Exceptions to this rule are permitted providing that they are for a valid reason (e.g. node module names, plugin/extension conventions etc)

## Repository Structure
Every repository must contain the following files in the root:

* .gitignore - Configured specifically for the languages that are used in the project
* README.md - Github flavoured markdown detailing the project, its licence, contributers and a rough changelog (Case of the filename must be observed to enable the labs site to pick it up)
* LICENCE-XXX - Each project must contain a Licence file, suffixed with a hyphen and an abbreviated name of the licence (For example LICENCE-MIT, LICENCE-MPL)

Every repository should contain the following directory structure unless there is a specific reason not to:
* src
* .gitignore
* LICENCE-XXX
* README.md

## Licensing
Wherever possible, flexible licenses like MIT, BSD, Apache should be used, use of any of the GNU GPL versions is strongly discouraged.
Licenses on third party dependencies must be compatible with the license selected for the project.

## Build tools
Wherever possible each project should provide an applicable build script for the environment it is designed to run in (and if possible, cross platform build tools)

## Unit testing
As the primary focus here is labs projects, unit tests are not a strict requirement but are strongly encouraged, and should be included where possible.

## Compiled output
Project repositories should not contain any compiled or otherwise obfuscated code (including but not limited to minified javascript and/or css).

## README files
Each projects README file should provide a meaningful description of what the repository contains, and at the bare minimum should contain some basic usage instructions.
The readme files should be formatted using Github Flavoured MarkDown and the file must be named README.md (This is in order for the labs site to render it correctly)

A sample README is available in this repository.

## Accreditations
Each contributer should be accredited in the README and applicable parts of the source code, this extends to the use of third party code snippets/libraries, if a project contains code from an external source the author should be mentioned and included in all significant portions of the software, regardless of whether the applicable code is public domain or free from other license restrictions.

## Changelog
* 22/04/2013 - Initial documentation

## Contributers
* Nick Pack

## Licence
Copyright (c) 2013 Cohaesus Projects Ltd 
Licensed under the MIT license.	