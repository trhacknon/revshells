# Revshells
Online Reserve Shell Generator 

# Features
'''
 Generate common listeners and reverse shells
 Raw mode to cURL shells to your machine.
 Button to increment the listening port number by 1
 URI and Base64 encoding
 LocalStorage to persist your configuration
 Dark and Light Modes
'''
# Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:
```
npx netlify dev
```

# Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container
```
docker build -t revshells
```

```
docker run -d -p 80:80 revshells
```
Browse to http://localhost:80
