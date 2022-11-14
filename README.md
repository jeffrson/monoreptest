# Repro

* execute `yarn install`
* see node_modules/@wstest/lib1 is a copy of the lib1.git, not a link to lib1 workspace,
  (besides, lib1 workspace has version 0.2.0 - so it is not a simple copy)
* see lib/lib1/node_modules which has a link to lib/lib1
