Option 1

A simple cloud shell tutorial instance

 - cloudshell_git_repo https://github.com/spurin/cloudshell-troubleshooting
 - tutorial = tutorial.md

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/spurin/cloudshell_testing.git&cloudshell_tutorial=tutorial.md)

Option 2

Extended further with the cloudshell_image set to the default parameter of gcr.io/cloudshell-images/cloudshell:latest

 - cloudshell_git_repo https://github.com/spurin/cloudshell-troubleshooting
 - tutorial = tutorial.md
 - cloudshell_image=gcr.io/cloudshell-images/cloudshell:latest

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/spurin/cloudshell_testing.git&cloudshell_tutorial=tutorial.md&cloudshell_image=gcr.io/cloudshell-images/cloudshell:latest)

Option 3

Default cloudshell_image override with gcr.io/graphite-cloud-shell-images/terraform as the image

 - cloudshell_git_repo https://github.com/spurin/cloudshell-troubleshooting
 - tutorial = tutorial.md
 - cloudshell_image=gcr.io/graphite-cloud-shell-images/terraform:latest

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/spurin/cloudshell_testing.git&cloudshell_tutorial=tutorial.md&cloudshell_image=gcr.io/graphite-cloud-shell-images/terraform:latest)
