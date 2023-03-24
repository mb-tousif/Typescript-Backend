# Setting Process for Typescript Backend Project

## Step 1

```bash
 npm init -y
```

## Step 2

```bash
 npm i typescript ts-node
```


## Step 3

```bash
 npx tsc --init
```

### I prefer the following snippet for tsconfig.json file

```bash
     {
      "compilerOptions": {
        /* Language and Environment */
        "target": "ES6",                                 
        /* Modules */
        "module": "commonjs",  
        "rootDir": "./",                                
        "outDir": "./dist",
        "esModuleInterop": true,
        "sourceMap": true,
        "forceConsistentCasingInFileNames": true,
        "strict": true,                                  
        /* Completeness */
        "skipLibCheck": true       
      },
      "include": ["**/*.ts"]
     }
```

## Step 4

```bash
 touch index.ts
```


## Step 4

```bash
 npm i express @types/express mongodb mongoose cors @types/cors
```
