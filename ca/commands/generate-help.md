# generate:help
Generate an implementation of hook_help()

**Usage:**
```
drupal generate:help [options]
gh
```

## Available options
Option | Details
-------|-------------
--module | Nom del mòdul.
--description | commands.generate.help.options.description

## Examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
