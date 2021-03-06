# NF-AS

NF-AS stands for **Nomad Fox Application Service**.  This application serves as the back-end for the Nomad Fox website.  It interacts with an S3 bucket to grab and create data, as well as CRUD operations with a MongoDB database.  Also authentication for users, with certain routes being protected via JWTs.

## Installation

**Server:** To get the app up and running, clone the repository, navigate to it in your terminal, and run `npm install`

**Database:** MongoDB is the database powering the application.  To set up MongoDB, try following [this guide](https://www.freecodecamp.org/news/learn-mongodb-a4ce205e7739/).

**Amazon S3:** You will need Amazon S3 credentials set up for some GET and POST requests. [Start here](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html).

## Running The Application

To run the application, run `npm start`.  Make sure your MongoDB instance is also running.

## Links

### [SoundCloud](https://soundcloud.com/nomad-fox)
### [Portfolio](https://lhuddlesto.com/)
