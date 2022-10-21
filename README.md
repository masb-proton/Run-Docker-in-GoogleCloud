# Run-Docker-in-GoogleCloud
Google Artifact Registry offers 300$ free docker process COOL!!!



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/masb-proton/Run-Docker-in-GoogleCloud/blob/main/Screenshot%20from%202022-10-21%2018-55-22.png">
    <img src="images/logo.png" alt="Logo" width="800" height="600">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/masb-proton/Run-Docker-in-GoogleCloud"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/masb-proton/Run-Docker-in-GoogleCloud">View Demo</a>
    ·
    <a href="https://github.com/masb-proton/Run-Docker-in-GoogleCloud">Report Bug</a>
    ·
    <a href="https://github.com/masb-proton/Run-Docker-in-GoogleCloud">Request Feature</a>
  </p>
</div>



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
