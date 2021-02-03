Ansible Role: Neo4j
=========

This role is for you to install **Neo4j**.  

If you want this role to support more applications, you can [**submit Issues**](https://github.com/websoft9dev/role_docker/issues/new/choose) for us.

## Requirements

Make sure these requirements need before the installation:

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu18.04 |
| Python version | Python2, Python3  |
| Runtime | Java |

Note: 

## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before:

```
roles:
  - { role: role_common }
  - { role：role_jdk }
```

## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| neo4j_version | 4.1 | String | No |


## Example

```
# Install a special version
neo4j_version: "4.1"

# Install the latest version
neo4j_version: "latest"
```

## Resources

* [Documentation](https://support.websoft9.com/docs/neo4j)
* [Deploy by Image](https://apps.websoft9.com/neo4j)
* [Deploy by Script](https://github.com/websoft9/ansible-neo4j)

## License

[LGPL-3.0](/License.md), Additional Terms: It is not allowed to publish free or paid image based on this repository in any Cloud platform's Marketplace.

Copyright (c) 2016-present, Websoft9

## FAQ

#### Is there any web-based GUI tool for Neo4j?

Yes, the Neo4j Browser is installed by default
