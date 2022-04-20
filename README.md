# dataware-tools

Dataware-tools are tools for researchers that enrich the value of data.

For more information about the tool, please refer the [document](https://docs.dataware-tools.com).


## Repositories

Roles or contents of the repositories in this organization are listed below:

| Repository Name | Contents                          |
| --------------- | --------------------------------- |
| app-\*          | Frontend web-applications         |
| api-\*          | Backend APIs for web-applications |
| docs            | This document                     |
| manifests       | Manifest files for deployment     |
| protocols       | API Specifications                |
| pydtk           | Python toolkit                    |
| test-infra      | Infrastructure for Dev/Ops        |
| web-deployment  | Common CI/CD                      |

Basically, web-applications in this organization depends on APIs separated into multiple repositories.\
So most of the applications do not work standalone.\
Please read the section below to use the applications.


## How to use?

### Python toolkit

Please refer [dataware-tools/pydtk](https://github.com/dataware-tools/pydtk).

### Web-based applications

A demo of our web-app is available at [https://demo.dataware-tools.com/](https://demo.dataware-tools.com).

If you want to deploy the application in you environment, please prepare a Kubernetes cluster and use the manifest files maintained in [dataware-tools/manifests](https://github.com/dataware-tools/manifests).


## Working groups

This project is maintained by the following working-groups.

| Group Name            | Purpose                                                          |
| --------------------- | ---------------------------------------------------------------- |
| `wg-deployment`       | Maintain manifest files and development / testing infrastructure |
| `wg-machine-learning` | Develop machine-learning related tools                           |
| `wg-web-app`          | Develop web applications                                         |

## Where can I get more help?

Please contact [contact@hdwlab.co.jp](mailto:contact@hdwlab.co.jp).
