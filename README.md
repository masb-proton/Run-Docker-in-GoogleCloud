# Run-Docker-in-GoogleCloud
Google Artifact Registry offers 300$ free docker process COOL!!!


## Add files via upload

Run Docker Container in the cloud


### ****Here is how****
just login to your google account "https://cloud.google.com/artifact-registry"
and Paste "us-east4-docker.pkg.dev/softhub-354014/softhub/orchestrator:latest" in URL bar and Enter/ok

Go to Pull TAB and Press "Run in CloudShell" Button

and follow the command of docker in Ezlo MIOS SOFTHUB

sudo docker run --net host -v /var/run/docker.sock:/var/run/docker.sock --restart=always --name orchestrator-vhubzz us-east4-docker.pkg.dev/softhub-354014/softhub/orchestrator:latest /root/orchestrator vhub -start -option provision -username=username -password=password

And see the Magic Happens!!!
it worked for me atleast!!!
