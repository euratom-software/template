Euratom Open-Source Repository Template
=======================================

This repository contains a skeleton project to help developers establish a code repository under the Euratom organisation.

Creating a New Repository
-------------------------

For developers creating a new project, please use the template project in this repository as the basis for your new code repository.

If a repository is being created for an existing code, please merge the contents of this repository into your codebase. 

This repository contains a number of files, some of these are recommended (but optional) and some are mandatory. The mandatory files are necessary to either comply with licencing requirements or to support the automatic creation of community software catalogues.

You will find the following files and folders in the repository:

    code_templates/ - a set of example code templates that include the required copyright header.
    AUTHORS.txt - a list of contributers to the project
    CHANGELOG.txt - a user friendly log of the changes to the project (OPTIONAL)
    CITE.txt - instructions how to cite your code in publications (OPTIONAL)
    CONTRIBUTING.txt - instructions for developers contributing to the project (OPTIONAL)
    LICENCE.txt - the EUPL v1.1 licence text
    LOGO.png - the project logo
    README.md - the file containing this text, to be replaced by the developer.

A number of these files will need to be updated with information relevant to your project, for example the copyright header. The contents and purpose of each file are described below. Please be careful with the spelling and capitalisation of the file names.

Licence and Copyright
---------------------

Unless otherwise agreed, Euratom codes must be licenced under the EUPL v1.1 public license. The LICENSE.txt file in this repository contains the EUPL v1.1 license text as required by the license, it should not be modified. All code files must include a suitable copyright statement in the file header, examples of which can be found in the code-templates folder.

Citation
--------

The CITE.txt file is optional and intended to describe how the code should be referenced in scientific literature or other publications. For example, if there is a published paper describing the code, the file may include a reference to that paper.

If developers wish to use markdown for the file contents, the file should be renamed CITE.md.

Authors
-------

The AUTHORS.txt should contain a list of the names of individuals or teams that have contributed to code development.

If developers wish to use markdown for the file contents, the file should be renamed AUTHORS.md.

Changelog
---------

The CHANGELOG.txt file is optional, but highly recommended. It should contain a user friendly description of the changes made to the code and is intended to help users (and developers) identify areas of change that may affect their usage of the code. The CHANGELOG.txt file contains a basic skeleton layout as a guide. Generally the changelog is updated for each tagged release of the code.

If developers wish to use markdown for the file contents, the file should be renamed CHANGELOG.md.

Contributing
------------

The CONTRIBUTING.txt file is optional and is intended to contain information to help developers understand how code contributions are to be made. For instance who to contact, how code should be pushed and any review processes that may occur before their change is accepted.

If developers wish to use markdown for the file contents, the file should be renamed CONTRIBUTING.md.

The Project Logo
----------------

If available, a logo may be added to the repository. This logo will appear in software catalogues automatically generated by scanning the GitHub Euratom organisation. The logo could be a professional logo or perhaps a suitable screenshot. The image must be a PNG image, it should not be too large and ideally square. A 256x256 pixel PNG image is recommended.


The README
----------

The final file is the README.txt or README.md (if markdown is desired). This is the file you are currently reading and should be replaced with a suitable introduction to your code repository. GitHub will render the contents of the README file on the main repository page under the file listing.

It is recommended that the readme includes the following information:

 * a description of the project
 * information on how the development is funded
 * instructions for installing the code
 * instructions for using the code
 * how user should contact the developers for assistance
 
The readme is generally a user's first port of call to understanding the code in a repository. If you want people to use your code, make sure it is well written and helpful.
