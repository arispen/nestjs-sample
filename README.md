### nest + mongodb sample
### Installation

first install dependencies
`npm install`

### Running

this app requres mongodb connection
see `app.module.ts` for connection options, and make sure there are matching options for the mongodb installation and the source code

Then, run the app:

`npm run start`

### interaction with the app

this app exposes 2 endpoints:

GET /cats for retrieving cats
and
POST /cats for adding new cats, see `src/cats/dto/create-cat.dto.ts` for the format of a new cat