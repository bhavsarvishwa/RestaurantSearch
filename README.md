## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Purpose
Open Table has a public API available at [https://opentable.herokuapp.com/](https://opentable.herokuapp.com/)
As an example, [http://opentable.herokuapp.com/api/restaurants?city=toronto](http://opentable.herokuapp.com/api/restaurants?city=toronto) returns a list of restaurants that deliver to Toronto, including some basic restaurant information.

### Platform
The following technologies are **required**:
- ReactJS
- Redux

### Goals
Provide a list of restaurants based on city, address, and name. Listed restaurants provide the following details:
- Name
- Address
- Price

Two (2) input controls are provided to users:

#### `city`
A string that is matched against city names in the database.

#### `refine` (optional)
An optional string, that filters the current list of restaurants based on the fields:
- Name
- Address
- Area

#### Additional Controls
Additional controls and filters are up to the developer's discretion.

#### Redux
Redux is used to store the following information:
- Name
- Address
- Area
