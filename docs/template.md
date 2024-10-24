# .template.json

```json
{
  "name": "typescript-blank",
  "description": "Create a blank project with TypeScript",
  "initParams": [
    {
      "name": "author",
      "message": "What is your name?",
      "type": "input",
      "default": ""
    },
    {
      "name": "packageManager",
      "message": "Choose a package manager",
      "type": "select",
      "choices": [
        {
          "name": "npm",
          "value": "npm",
          "description": "NPM Package Manager"
        },
        {
          "name": "yarn",
          "value": "yarn",
          "description": "Yarn Package Manager"
        },
        {
          "name": "pnpm",
          "value": "pnpm",
          "description": "PNPM Package Manager"
        }
      ],
      "default": "npm"
    },
    {
      "name": "useLogger",
      "message": "Select DB",
      "type": "checkbox",
      "choices": [
        {
          "name": "Mysql",
          "value": "mysql",
          "description": "Mysql Database"
        },
        {
          "name": "Postgres",
          "value": "postgres",
          "description": "Postgres Database"
        },
        {
          "name": "Mongodb",
          "value": "mongodb",
          "description": "Mongodb Database"
        }
      ]
    },
    {
      "name": "continue",
      "message": "Do you want to continue?",
      "type": "confirm",
      "default": true
    }
  ]
}
```
