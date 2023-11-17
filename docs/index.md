# Welcome to mike with python semantic release

Mike-PSR for short ?

This is a documentation commit-versioned that do many thing automatically. Such wow

This is a small side project, go read PSR and mike documentation if necessary. 
I won't document much.

Workflow:

You have a project to document, and you want your old doc to be accessible.

- You dev on another repo
- Version bump on your project
- You change the documentation with your changements
- You commit with "fix:", "feat:" or tuned Commit Parser
- PSR check commit, eventually make new release
- On new release, mike set new version for documentation
- On old release, mike update content of old documentation -> This can be blocked
- Use Github Pages static job to release from actions

Using PSR>=8.0, you may want to use the template feature,
to update things on new release. PSR 8 is pretty powerfull.

