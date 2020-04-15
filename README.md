# blockstack
Demo blockstack authentication 

# bundle.js (https://cdn.jsdelivr.net/gh/mallond/blockstack/bundle.js)

https://gomakethings.com/how-to-turn-any-github-repo-into-a-cdn/

# Notes

Run the docker comand.  

  docker run -P -d -v "/home/coder/project:/home/coder/project" codercom/code-server


To get the password, enter 

  docker logs <image>  
  
# HTTPS Server
```
> openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
> http-server --cors -S -C cert.pem
```
