# unraid-repository
unRAID app and plugin repository for community applications app store

# Usage with the CA plugin
Add to your Repositories.json
```
 {
    "name": "eXtremeSHOK's Repository",
    "url": "https://github.com/extremeshok/unraid-repository",
    "forum": "https://github.com/extremeshok/unraid-repository/issues",
    "profile": "https://forums.unraid.net/profile/86139-extremeshok"
  },
```

# Usage without the CA plugin
unRAID ver 6.0.0 or later
* Navigate to the "Docker" tab and then the "Template Repositories" sub tab
* Enter in a URL of https://github.com/extremeshok/unraid-repository in the "Template repositories" field
* Click on the "Save" button
* Navigate to the "Docker" tab and then click on the "Add Container" button
* Click on the "Template" dropdown menu and select the desired Docker image
* Click the "Advanced View" toggle on the top right and fill in required fields e.g. volume data, environment variables etc
* Click on the "Create" buttonhttps://forums.unraid.net/profile/86139-extremeshok/ at the bottom of the window to begin pulling down the Docker image
once the image is downloaded you should see it appear in the "Docker Containers" sub-tab
