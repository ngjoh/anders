---
title: Chain Template
description: Version 1 of the "Chain" template to be used for 365admin
---

# Koksmat Chain Template

This is the first version of the "Chain" template to be used for 365admin. The purpose of this template is to provide an easy way to bootstrap a new workspace that that can be used to host a chain of workspaces.



## Folder Structure

The folder structure is as follows:

```
    "root"
    ├── workspaces                        Root of workspaces
    │   ├── .koksmat                      Root of connections
    │   │   ├── tenants
    │   │   |  ├── <tenant-name>
    │   │   |  |  ├── <connection-A>
    │   │   |  |  ├── <connection-B>   
    │   ├── timesheets-registration       One workspace
    │   ├── timesheets-approval           Another workspace
    │   │   ├── .koksmat                  koksmat app space
    │   │   │   ├── app
    │   │   │   ├── sessions
    │   │   │   ├── web
    │   │   │   ├── workdir    
    
```
