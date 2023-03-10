# Multi-channel Integration Layer APIs
OpenAPI descriptors of the services that make up the Multi-channel Integration Layer of SW Client project.

## WARNING
Azure API Manager does not accept OpenAPI descriptors with references to other files.

For this reason a pre-commit hook has been created which creates a normalized version of the descriptors.

To use the pre-commit hook, perform the following steps:
```shell script
cp utils/pre-commit .git/hooks
chmod +x .git/hooks/pre-commit
```

In this way, every time a commit is done, the normalized version of the descriptors will be created and committed automatically.