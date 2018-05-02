## Our Final Docments or Final work

# Linux Stars Team

### Team Memebers
#### Abshir Ali (Support)
#### Chinou Vang (Researcher)
#### Mussie Asarat (Support)
#### Shue Lee (Documentation)
#### KongMeng Lee (Testing)
#### Our Project Link(https://github.com/kml74123/Web-Server-Team/projects/2)


### We Love to share our document and how is work with all steps.
Step 1:
First we need to update your system if you haven't already, to do this run the command sudo apt-get update
Also most importantly, ssh into our sootsplash server! ssh (git hub username)@sootsplash.csci2461.com


Step 2:
Next we install apache by running:sudo apt-get install apache2


Step 3:
To see if you have successfully installed apache, run the command sudo systemctl status apache2. You should see a green highlighted word that says apache is active.


Step 4:
In order to go do the next step, we must restart apache really fast by running systemctl restart apache2


Step 5:
Now we must make a public_html directory! To do that run mkdir public_html


Step 6:
Now we just need to make the script for the website! Run the command sudo nano/home/(your own user)/public_html


Step 7:
Now you nanoed into your webpage script have some fun with it! but since you're just starting just put Testing User Dir Page' just for the heck of it!


Step 8:
Almost done! Now that you have your test script ready you are ready to deploy your test page! At the like at the top put https://sootsplash.csci2461.com/~(your own user)/

