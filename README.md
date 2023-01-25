# Build execution environments with `ansible-builder`
## Building execution environment images for use in [ansible workshops](https://github.com/ansible/workshops)
### This repo responds to modifications on `main` by building a new container image with Github Actions to be used as an execution environment for Ansible Automation Platform 2.

[![ServiceNow EE build](https://github.com/styxxen21/ee-builds/actions/workflows/servicenow-ee-build.yml/badge.svg)](https://github.com/styxxen21/ee-builds/actions/workflows/servicenow-ee-build.yml) [![VCC EE build](https://github.com/styxxen21/ee-builds/actions/workflows/vcc-ee-build.yml/badge.svg)](https://github.com/styxxen21/ee-builds/actions/workflows/vcc-ee-build.yml) 

![workflow](https://user-images.githubusercontent.com/8515817/140567781-616a7507-607e-41af-b668-4d3850776dc9.png)

### Contributions
The directories in this repository should follow the format that `ansible-builder` expects. See [servicenow-ee](https://github.com/cloin/ee-builds/tree/main/servicenow-ee) as an example. The name you give the directory should also be the name of the image. You can also copy the [servicenow-ee workflow](https://github.com/cloin/ee-builds/blob/main/.github/workflows/servicenow-ee-build.yml) file and adjust the parameters on lines 2 and 25-27. Questions? Open an issue!


### Useful documentation and links
- [Ansible Automation Platform](https://www.ansible.com/products/automation-platform)
- [ansible-navigator](https://github.com/ansible/ansible-navigator)
- [ansible-builder](https://github.com/ansible/ansible-builder)
- [GitHub Actions quickstart](https://docs.github.com/en/actions/quickstart)
- [GitHub environments](https://docs.github.com/en/actions/deployment/using-environments-for-deployment)
- [redhat-actions/podman-login](https://github.com/redhat-actions/podman-login)
- [redhat-actions/push-to-registry](https://github.com/redhat-actions/push-to-registry)
- chcon system_u:object_r:usr_t:s0 runsvc.sh - command to get github runner to run as service.


