Solution:
- Push to local server as well as GitHub
- When the server receives a push, it runs a git hook.
- The hook pulls the latest website files from GitHub,
then transfers files from the resume project to the website. 
- It then pushes the changes to GitHub, and makes a pull request to 
include changes into the main website repository.
- GitHub then sends me an email about the pull request. 
- I can then review changes, and approve the pull request if everything
looks good. 

Problems:
- Two GitHub accounts is probably not necessary. I started out with
two accounts since I was originally using a remote server, and 
wanted to keep my main GitHub account secure. 
- Making the JavaScript/HTML files still happens on my computer.
It would be nice for the server to do HTML processing. 
- Currently when I push changes to my resume project, it takes a few 
seconds, and there is good bit of output. It might be nice to change It
so that the process happens in the background and I don't have to 
wait for it to finish. 