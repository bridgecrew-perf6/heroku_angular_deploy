# heroku_angular_deploy

# 1.Move devDependencies to dependencies
    "@angular/cli": "xxx",
    "@angular/compiler-cli": "xxx",
    "typescript": "xxxx",
    "@angular-devkit/build-angular": "xxxx"

# Config 
"engine" : {
    "node": "xxxxxxx",
    "npm" : "xxxxxx"
}

# Start Script
"start" : "ng serve --port $PORT --host 0.0.0.0 --disable-host-check",

# Add Script
"postinstall" : "ng build --output-path angularapp --aot --prod"