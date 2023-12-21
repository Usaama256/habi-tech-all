# Habi-Tech 
The Perfect solution for your automation, Is made up of two componets; the client and the server.
## Live Demo
<a href="https://habitech.azurewebsites.net/">Live Preview</a>
### Login Test Credentials
```
{
  "Email": "sama.dev@habitech.iot",
  "Pass": "!wa30~03dq#"
}
```
```
{
   "Email": "test.dev@habitech.iot",
   "Pass": "03dq#~!wa30"
}
```
## API Test and Documentation
### User
<a href="https://app.swaggerhub.com/apis-docs/USAAMANKANGI/User/1.0.0#/default/post_habitech_api_login">View Docs</a>

### Lights
<a href="https://app.swaggerhub.com/apis-docs/USAAMANKANGI/Lights/1.0.0#/default/get_habitech_api_switchlight__device_id___action___user_Id_">View Docs</a>

## Client
The Client is a ReactJs project built using TypeScript and Vite.js
### Program Structure
```plaintext
- public
- src
  - assets
    - gallery
  - components
    - cameras
    - common
    - doorsWindows
    - energy
    - gadgets
    - layouts
    - lights
    - login
    - navigation
    - overview
    - security
    - temperature
    - weather
  - hooks
  - routing
  - services
  - store
  - utils
    - apiCalls
    - redux
    - slices
```
### Local Setup
To get a local copy of the code, clone it using git:

```
git clone https://github.com/Usaama256/habi-tech-all.git
cd ./habi-tech-all/habi-tech_client
```
Install dependencies:

```
npm install
```

Now, you can start a local web server by running:

```
npm start
```

And then open http://localhost:6117 to view it in the browser.

## Server
The Server is an ASP.NET Web Api imlementation built with C#
### Program Structure
```plaintext
- habi-tech_server
  - docs
  - HabiTech
    - bin
      - Debug
        - net8.0
    - Controllers
    - Database
    - Models
    - obj
      - Debug
        - net8.0
    - Properties
    - Services
    - wwwroot
  - Habitech.Contracts
    - bin
      - Debug
        - net8.0
    - Lights
    - obj
      - Debug
        - net8.0
    - User
  - requests
    - lights
    - user
  - sql
```
### Local Setup
To get a local copy of the code, clone it using git:

```
git clone https://github.com/Usaama256/habi-tech-all.git
cd ./habi-tech-all/habi-tech_server
```
Install dependencies:

```
#
```

Now, you can start a local web server by running:

```
dotnet run --project ./HabiTech
```

And then open http://localhost:5014 to view it in the browser.
