# featmap-docker
pre-built featmap docker image &amp; configuration.

[featmap](https://github.com/amborle/featmap) is a simple and open source user story mapping tool. But it is not easy to build from the source code. Here is a pre-built Docker image and configuration file.

## How to install

1. clone code to local.
2. Execute in the project directory: `docker compose up -d`

## How to use

Use the browser to visit http:// localhost: 5000 will open the Featmap login page. When you use it for the first time, you need to click on the `Create An Account` link to create a user.

## How to backup data

1. Execute in the project directory: `docker compose down`
2. Back up all the files in the `data` subdirectory.
3. Execute in the project directory: `docker compose up -d`