# Run-Docker-in-GoogleCloud
</br>
Google Artifact Registry offers 300$ free docker process COOL!!!
</br>
</br>
</br>



<br />
<div align="center">

[![Product Name Screen Shot][product-screenshot]]
  
</div>
</br>
</br>
</br>
Run Docker Container in the cloud
</br>

### ****Here is how****

</br>

Just login to your google account "https://cloud.google.com/artifact-registry"
and Paste in URL bar and Enter/ok
</br>
``
us-east4-docker.pkg.dev/softhub-354014/softhub/orchestrator:latest``
</br>


Go to Pull TAB and Press Button</br> ``Run in CloudShell`` </br>

and follow the command of docker in Ezlo MIOS SOFTHUB
</br></br>

``sudo docker run --net host -v /var/run/docker.sock:/var/run/docker.sock --restart=always --name orchestrator-vhubzz us-east4-docker.pkg.dev/softhub-354014/softhub/orchestrator:latest /root/orchestrator vhub -start -option provision -username=username -password=password``
</br></br>

And see the Magic Happens!!!
it worked for me atleast!!!


[product-screenshot]: images/screenshot.png
