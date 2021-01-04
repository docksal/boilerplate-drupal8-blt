# BLTed powered by Docksal

A base or sample Drupal 8 project defined by Acquia BLT and powered by Docksal.

BLT is an open-source project template and tool that enables building, testing, and deploying Drupal installations following Acquia Professional Services' best practices.

Docksal is a Docker tool for building containerized development environments. From a zero-config setup to a fully customized build, along with the command-line tool `fin`, Docksal provides a powerful and flexible development platform.

## Getting Started

You must first have [Docksal installed](https://docs.docksal.io/getting-started/) and setup on your computer.

If you are using an Acquia Cloud production environment, follow instructions for [adding your Acquia Cloud API key](https://docs.docksal.io/tools/acquia-drush/) to the Docksal environment.

To use this project as a starter, clone this repo to your local machine.

From your terminal, go to the directory where you have cloned the repo and enter the following command:
```
fin init
```

A `composer.lock` file and a `salt.txt` file will be generated. These files should be committed to your repository.
When complete, you can access the site by running:

```
fin drush uli
```

Additional [BLT documentation](https://docs.acquia.com/blt/) may be useful. You may also access a list of BLT commands by running:
```
fin blt
```

Additional [Docksal documentation](http://docs.docksal.io) may also be helpful. You can access a list of commands simply by running:
```
fin
```

## Working With a BLT Project

BLT projects are designed to instill software development best practices (including git workflows).

Acquia BLT Developer documentation includes an [example workflow](https://docs.acquia.com/blt/developer/dev-workflow/).

### Important Configuration Files

BLT uses a number of configuration (.yml or .json) files to define and customize behaviors. Some examples of these are:

* blt/blt.yml (formerly blt/project.yml prior to BLT 9.x)
* blt/local.blt.yml
* box/config.yml (if using Drupal VM)
* drush/sites (contains Drush aliases for this project)
* composer.json (includes required components, including Drupal Modules, for this project)

## Resources

* [BLT Documentation](https://docs.acquia.com/blt/)
* [BLT GitHub](https://github.com/acquia/blt)
* [Docksal Documentation](http://docs.docksal.io)
* [Docksal GitHub](https://github.com/docksal/docksal)


**BLT v10.5.0**
