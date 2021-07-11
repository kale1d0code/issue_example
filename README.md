# monorepo-builder issue repo

to reproduce issue run the following commands

* composer install
* composer run validate-repo (or any command for vendor/bin/monorepo-builder) 


this project is based on microsofts [php dev container](https://github.com/microsoft/vscode-remote-try-php.git) for use with vscodes remote-containers plugin.

I am not sure if running the package in a dedicated dev container is causing the problem but this will be the same environment I am using.


When opening the project in vscode it should prompt to run within a dev container but this isn't necessary if php is installed on the host machine.

The supplied monorepo-builder config and packages where generated with the init command.

I installed ecs to demonstrate the issue with the ContainerConfigurator class is only effecting monorepo-builder.php