## Talent Pro Assignment 2
### How to Examine
The Assignment is consists of a api server which is developed on top of Nest.js, Apollo GraphQL, MongoDB and a client with reat Next.js, Apollo Client. When doing this assignment I follow the best practice for production ready solution. Originaly this assignment has four different server. One for serving the API, one for client, one for Database that is MongoDB cloud Atlas and one for Media files storage that is Cloudinary. All servers are doing their job efficiently, so there is no performence related issue and Seperation of concern maintained very well. 
### Docker
To dockerize the assignment I used two separate Dockerfile one for client another for server instade of docker-compose.yaml file, because of I didn't able reched that level within very short time. Besides I didn't have docker environment in my machine to tests the docker is running properly, beacuse I have a doubt, my pc may not be able to run docker smoothly for low configuration.

To examine the project please nevigate to the project server folder and run with terminal/command prompt

```bash
yarn
```
to install server dependencies

then create a .env file in server root folder and copy the content form .env.example

then start api server with 

```bash
yarn start:dev
```
a development server will starts at http://localhost:4000, if you want to goto GraphQL API endpoint then goto http://localhost:4000/graphql

Now goto the client folder and run with terminal/command prompt

```bash
yarn
```
to install client dependencies

After that run

```bash
yarn dev
```

a Next.js development server will start at http://localhost:3000 

Now goto http://localhost:3000 with your browser to examine




