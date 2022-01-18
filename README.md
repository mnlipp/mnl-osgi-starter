Starter Workspace/Project for OSGi based development
====================================================

Usage
-----

Clone the project, remove `.git`. Change the top project's name in
`settings.gradle`. Adapt the pattern for including projects.

Replace the `LICENSE.TXT` with yours. Replace this README.

Building
--------

The project is organized as a `bnd` 
[workspace build](https://github.com/bndtools/bnd/blob/master/gradle-plugins/README.md#gradle-plugins-for-bnd-workspace-builds).
The bundles can 
be built with `gradle build`. For working with the project in Eclipse 
run `gradle eclipse` before importing the project. Make sure that you 
have installed [Bndtools](http://bndtools.org/).
