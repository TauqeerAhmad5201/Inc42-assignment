
## Combination of Go, Next.js and Wordpress

Project contains the Combination of the application based on Go Lang, Next.js and Wordpress. 


## Prerequisites

+ git
+ Docker 
+ Docker-compose 
+ VS Code (optimal for Next.js linting)
+ UNIX System (preferred)


## Setting it up 

```
sudo docker compose up
```

## To follow up 

The project contains some settings for vs code the Next.js linting. Do add those JSON to your settings. 

```
{
  "editor.rulers": [80, 100, 120],
  "workbench.colorCustomizations": {
    "editorRuler.foreground": "#FF69B4"
  },
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.formatDocument": true,
    "source.fixAll.eslint": true
  }
}
```

## About project structure

Division of project goes like: 

+ Workflows (pipelines)
+ Go-application
+ Nextjs-application
+ Wordpress-application
+ docker-comppose.yml 


## Note to developers
 
Feel free to contribute to the project and keep in mind about the ports of the project. Also, please follow a proper contributing guidlines to ensure stability. 