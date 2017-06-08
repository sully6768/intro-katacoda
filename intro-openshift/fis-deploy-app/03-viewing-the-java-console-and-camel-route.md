While a build is running, the _Overview_ page will display a banner. The build may take a couple of minutes to start running because OpenShift needs to download the dependent jars needed for this project.

![Build Progress Banner](../../assets/intro-openshift/fis-deploy-app/03-build-progress-banner.png)

To view the output of the build as it is running, click on _View Log_. This will bring you to the _Logs_ tab of the _Pod_ for the build which is running.

![Running Build Log](../../assets/intro-openshift/fis-deploy-app/03-running-build-log.png)

Click on _Follow_ at the right hand side to see the latest log output as it is being produced.

If the banner is not visible, you can access build logs by selecting the _Builds_ menu and then selecting _Builds_.

![Accessing Builds Menu](../../assets/intro-openshift/fis-deploy-app/03-accessing-builds-menu.png)

This will bring up a list of builds which are currently running, as well as builds which have completed. 

![List of Builds Run](../../assets/intro-openshift/fis-deploy-app/03-list-of-builds-run.png)

Select on the build number of the last build to bring up the details for the build.

![Build Details](../../assets/intro-openshift/fis-deploy-app/03-build-details.png)

Select on the _Logs_ tab to bring up the log output for the build.


##???? WHERE DID THE JAVA CONSOLE GONE TO ?????###