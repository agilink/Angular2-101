
# Angular2 - Seed

Base project for Angular 2

## Prerequisites
    
    - Node JS, installed and configured in Path (check node -v, should be > 5.x.x)
    - Git installed and configured in path( check git --version, should be > 2.8.x)
    
    
open command window at project root and run below commands
   ```bash
     # this will install typescript and typings node module globally
     npm install typescript -g
     npm install typings -g
     npm install gulp-cli -g
     
     # detour : check versions of all the necessary tools before proceeding 
     # it should be equal or higher than below
     npm -v # ^3.8.3
     tsc -v # ^1.8.10
     git --version #  2.8.1.windows.1 (equivalent for Mac)
     typings -v  # ^0.7.12
     # also make sure if you are behind company firewall you make necessary proxy chnages for node and typingsrc
     
     # below commands will install all node package required
     npm install
     
     # below command will compile all ts files to js, less to css and move html files 
     # to a dist folder ready to be deployed.  
     gulp
   ```   
     
## Generating and serving an Angular2 project via a dev server
 ```bash  
# Below command runs node based lite-server and serves the application
npm run dev
```   
     
## Note 

If you are bhind firewall make sure you update proxy setting for NPM.
```bash
npm config set proxy http://proxy.company.com:8080
npm config set https-proxy http://proxy.company.com:8080
```  
        
Similarly for typings update proxy in .typingsrc 
```bash
{
 "proxy":"http://proxy.company.com:8080"
}
```

## Issues
-- You may face issue with path of node and typescript make sure you check version of the same.


    

