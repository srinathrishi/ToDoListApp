Log in to Jfrog using your username and password.
Click on "Artifactory" on the left-hand pane, then click on "Artifacts".
Click on the "Set Me Up" button in the top-right corner of the screen.
In the widget that opens, select "PyPI" as the Python package type from the dropdown menu.
Choose the appropriate repository name from the dropdown menu.

In the Configure tab, enter your username and password to insert your credentials. Once you enter the credentials, click on the lock symbol to generate an API key/token.

Go to the Deploy tab for deploying your packages and configure your .pypirc file in the home directory. If you want to resolve packages, you can use pip.conf in the home directory. In both cases, use the API key/token generated in step 8 to authenticate with JFrog Artifactory. Instructions for configuring .pypirc and pip.conf files are provided in the Resolve tab.
