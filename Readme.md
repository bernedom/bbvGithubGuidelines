# Github @ bbv

Over the last few years GitHub has become one of the major plattforms for interaction between technically-minded people. As such it should be considered more than just a data-dump for git repsitories and be treated like any other social media plattform. This is especially true if one makes use of the github.io plattform for git-based blogging. At bbv we are actively advertising good software crafmanship on all levels ranging from using CleanCode over providing simple build toolchains to encouraging developer-friendly and efficient workflow. Because of this this values and techniques should be part of our natural way of working and thus be reflected in the work we publish over github. 
This document serves as a guide and base standard to setup and maintain repositories for bbv on github.

## Structure

Each github repo should provide at least these items in the root folder
 * Readme.md - Containing what this project is about, setup/build instructions
 * LICENSE - The license the project is under
 * Source directory
 
 ### Contents of the read me
 @Todo make example/skeleton
 
 The Readme should at minimum contain these items: 
 
 * __Project Summary__ - What is this repository about? What problem is solved by this code? Why does it exist at all?
 * __The current release__ - Link to a download of a pre-built and packaged release if applicable.
 * __Setup/Build - Instructions___ - Describe how to set up and build the project as simple as possible. This can be as simple as running a docker container
 * __Brief user manual__ - Once the users have built the project, how do they run it for the first time? 
 
 ### License
 Pick a reasonably common opensource license for your repository such as a flavor fo GPL, LGPL, MIT or other. Generally projects hould be open sources and as free as possible. If you have any non-free content consider if this should be a project hosted on a public github repository at all. 
 
 ### Sources & Documentation
 The code should be buildable for every published commit with the instructions provided. If building is especially tricky try to provide things like a docker container or helper scripts. Consider linking other github projects using submodules. Any program code should reflect the coding standards such as clean-code we advertise at bbv, this includes appropriate documentation. The documentation should be fully publicly available, do not link to any internal resources such as the bbv-wiki or onedrive.  
 
## Workflow
Use a workflow in the repository that matches the best practices we encourage our customers to use. Generally prefer a pull-request based workflow to directly pushing changes into master. Encourage contributors to use a clean workflow as well.