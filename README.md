# chef-client Jenkins Plugin

Allows a Jenkins server to have multiple installs of the Chef Client.  Then a job can pick the specific version to be used to communicate to the Chef Server.

Is is similar to the Maven or Java plugin in Jenkins that expose a dropdown of the version of Maven or Java (JDK) to use for a specific build.

Generally there is not much conern about which version of the chef-client or knife is being used, but there are times where using the same version for developers and automation tools can help ensure consistency in behavior.

## TODO
* get a list of Chef Client versions, store it json/xml in Jenkins.  Have a default list.
* Make the list be self updating by hitting a button?
* Ability to select an already installed version on the Jenkins box and name it
* Support for Jenkins box w/o Internet access
* May as well allow install of Chef DK (warn for massive download size)
