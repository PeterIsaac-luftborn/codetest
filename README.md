# Codetest

# Requirements
  - [Nodejs](https://nodejs.org/en/)
  - [Dotnet core 3.1 Runtime](https://dotnet.microsoft.com/download/dotnet-core/3.1)
  - [Dotnet core 3.1 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1)

# Before we start
  - Clone repository
  - Install dependencie (should be done automatically when running the project):
```sh
    cd Frontend
    npm i
    dotnet restore
```
### Run:
  - Use the debug function in either visual studio or vs code
  - Or just run this command:
```sh
dotnet run Frontend/Frontend.csproj
```

# Gerneral information about the project
The project is a standard dotnet core 3.1 MCV project.

No libraries are used in the javascript. We utilize Gulp to bundle and compile both the TypeScript and the SCSS.

# Database
  - We use a mongodb for this project, but feel free to switch if you prefer another option.
  - The database is publicly open, and the connectionstring in the appsettings.json is filled in, ready and working.

# Controllers:
## Modal Controller:
Modal controller returns html from a view. Useful in e.g. modals or ajax like calls.
  - [Route("api/[controller]/[action]")]
  
## User Controller:
Get users, update users, delete users.
  - [Route("api/[controller]/[action]")]

## Home Controller:
Returns your base-view.
  - [Route("[controller]/[action]")]
  
# Test objectives:
In general, we want to have at least some code in the following three languages.
  - C#
  - Javascript (TypeScript)
  - CSS (SCSS)

Using any external library is allowed, the same goes for old code in your repository. Utilizing external libraries does have to be utilized for a good reason though.

## Surggestions to the test
### Web Components
Web components are always preffered as its cross platform compatible, and are modular. If you could create one web component, it would be very much appreciated, even though it might be simple.

### Login
Login functionality might be a great addition. We almost always need to implement login on our soulutions.

### Improve layout (optional)
The current layout is very simple, if you could improve it, it would be a big benefit.

### Improve logging (optional)
logging can always be improved, see if you could add your touch to the logging.

### UnitTesting (optional)
Unit testing could be a very nice addition to this project.

# What do we find important
- Think scalable. Our solution needs to be maintainable and scalable.
- Write readable code, with meaningfull function and variable names
- Extract your code to classes where a class or a function only have one specific purpose
- Only write comments, if code is not self-explainatory(which it should be for the most part)
- Try to write your own code. Importing libraries has to be for a good reason. We rate it very highly that you are able to write your own code
- Remember logging. Any project without logging will never be production ready.

# Write pretty code
- We have some coding guidelines that we would like all our code to follow, it would be nice if you could read it, and follow it as much as you can.

	- [The overall guidelines](https://github.com/luftborn-ivs/design-guide)

	- [C#](https://github.com/luftborn-ivs/design-guide/blob/master/c%23/readme.md)

	- [Javascript](https://github.com/luftborn-ivs/design-guide/blob/master/js/readme.md)

	- [SCSS](https://github.com/luftborn-ivs/design-guide#styling)