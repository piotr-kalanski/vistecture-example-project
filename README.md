# vistecture-example-project

Example documentation of (micro) service oriented architecture using https://github.com/AOEpeople/vistecture

## Generate documentation

### Prerequisite

- Install go
- Install dot
- Install vistecture

    go get github.com/AOEpeople/vistecture

### Generate html documentation

    vistecture --config=cloud_team_project/project.yml documentation --iconPath=templates/icons > documentation.html

### Serve documentation

     vistecture --config=cloud_team_project/project.yml serve

## Useful information

### Documentation template

Visteture enables creating documentation template which - example is at [templates/htmldocument.tmpl](templates/htmldocument.tmpl).

Other templates: https://github.com/AOEpeople/vistecture/tree/master/templates

Domain model with all available metadata is here: https://github.com/AOEpeople/vistecture/tree/master/model/core
