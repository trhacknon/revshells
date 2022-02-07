# reverse-shell-generator
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-14-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Hosted Reverse Shell generator with a ton of functionality -- (great for CTFs)
<br> [![Netlify Status](https://api.netlify.com/api/v1/badges/46dbabe0-23b7-42e6-b04b-e1769dc455ce/deploy-status)](https://app.netlify.com/sites/brave-swartz-5dcdab/deploys)

### Hosted Instance
https://revshell۔hackerwasii.com

### Features

- Generate common listeners and reverse shells
- Raw mode to cURL shells to your machine.
- Button to increment the listening port number by 1
- URI and Base64 encoding
- LocalStorage to persist your configuration
- Dark and Light Modes

### Screenshot

![image](https://user-images.githubusercontent.com/44453666/111888563-02430f80-89b4-11eb-9e17-ea3de014cf69.png)

## Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:

```
npx netlify dev
```

## Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container

```
docker build -t reverse_shell_generator .

docker run -d -p 80:80 reverse_shell_generator
```

Browse to http://localhost:80
