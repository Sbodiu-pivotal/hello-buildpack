Get started with buildpacks
Usage

To use this buildpack specify the URI of the repository when pushing an application to Cloud Foundry:

    $ cf push <APP-NAME> -p <ARTIFACT> -b https://github.com/sergiubodiu/hello-buildpack.git
