# aspnetcore-vuejs-template

This is a simple template that combines VueJS and .NET Core MVC application. It allows you to use Vue components inside Razor view engine. It uses [Parcel](https://parceljs.org/) as a bundler, and npm as a package manager for client side libraries. Bundled assets are stored in ```wwwroot/dist``` directory.

## NPM scripts explained
* **dev**: Allows hot-reloads on vuejs and .net core application. It uses commands ```parcel watch``` and ```dotnet watch run``` to monitor changes on files in the project. 

* **production**: Minify and bundle your assets for production, and pack your .net core application. It uses the ```parcel build``` command to bundle the VueJS application and ```dotnet publish``` command to pack your porject in the ```publish``` folder for production. 

### Note:
- **dev** is using [concurrently](https://www.npmjs.com/package/concurrently) node module.



## Project setup
```
npm install
```

### Compiles and hot-reloads your app for development
```
npm run dev
```

### Packages your app for production
```
npm run build
```

### Stops running servers, if they exist
```
npm run stop
```
