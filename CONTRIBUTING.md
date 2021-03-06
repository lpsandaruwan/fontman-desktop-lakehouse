#How to contribute to Fontman Project

We welcome bud reports, feature requests, suggestions, code contributions and any other form of contribution to the project given that it aligns with the product roadmap, philosophy and the plans laid out by the community and the core developers. (Checkout the issue tracker and milestones for the roadmap until we publish a more documentation)   
We want to keep it easy a possible to contribute without breaking the code or stability of the project. So there are few guidelines that we recommend contributors to follow, and please note that maintainers will not hesitate to say “no” to contributions if they do not follow these guidelines mentioned below. You can always send a pull request to discuss changes to these guidelines :)


###About Fontman project
The aim of Fontman (stands for font manager) project is to provide efficient, user-friendly and sustainable systems, tools and standards for managing, distributing and consuming fonts on multiple production platforms and workflows. Fontman software stack is the backbone of this scheme and is made of a few different components make sure we have a flexible set of tools that can achieve the expected functionality while maintaining an integrity of the code.
Fontman project is led by a group of graphic designers, typeface designers, font developers and software developers interested in font and text technologies and free software. Thus the project is heavily focused on making functionally as well as beautiful software. We are actively seeking for contribution in any form to take the project forward. We strongly encourage you to take a look at the issue tracker to see how the community resolve issues to get hold of the philosophy of the project before contributing. (We will do better documentation by Ocotber 2017)
 [fontman-server](https://github.com/fontman/fontman-server) provides a sustainable API for Fontman offcial desktop client and other Fontman API seekers. Fontman client also follows a client-server architecture, and it is made of two components: the [fontman-desktop-core](https://github.com/fontman/fontman-desktop-core) and the [fontman-desktop](https://github.com/fontman/fontman-desktop). `fontman-desktop-core` is the backend of the [fontman-desktop](https://github.com/fontman/fontman-desktop) GUI client, and it handles the font management tasks and Fontman server API consuming. `fontman-desktop` is a GUI desktop application with a beautiful and efficient user interface for managing font services from the Core.


###Getting started

Make sure you have a GitHub account.
Submit your suggestions, questions and requests as an issue on the appropriate repository. Fontman-Desktop issue tracker is the general tracker for the project and if you are not sure which issue tracker to report, use it.
Please check the milestones, roadmap and docs before starting your work if you intend to contribute upstream and mainline Fontman stack.


###Making changes

####API changes
Make sure you have well discussed the issue and understand the behaviour.
API changes are critical, can lead working components to incompatible behaviours and it will cost Fontman to change the major version, so do not do anything unless you have a clear idea.
Thus this is critical; it will take a long period to merge changes, until other components are lined up with the latest API changes.

####Bug fixes
Make sure you have tested properly, and stability of other dependent components after patching.

####Coding style
For Python follow the PEP-8 coding guidelines.
For JavaScript, the code must be ECMAscript 6 standardised.

####Models and entity changes
Make sure you have a clear knowledge about Fontman models and architecture. Do not hesitate to post an issue on the relevant issue tracker
Pull requests with model changes will not be accepted until the issues have been well discussed.
If model changes lead to appropriate API changes, please follow the guidelines mentioned in API changes also.


####Submitting changes

<TODO>
