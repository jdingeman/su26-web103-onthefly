## Clarifications

- Immediate error: `/src/pages/TripDetails.jsx` is not provided with an export named 'default'. Front end crashes trying to import a component that hasn't been defined, but checkpoint 0 expects the student to see the homepage without changing anything in the provided code.
- Front end code is provided without the vite.config.js proxy set.
- Step 2: Says to look for event handling function called `createTrip()` but no such function exists. It's provided as `createPost()`
- Step 3: Same issue as Step 2
- Step 4: Says to call `setDestinations` but the function is `setDestination`
- Step 4: The front end route for creating a new destination is defined as `destination/new/:id` but this doesn't make sense.
  - 1. There is no button to create a new destination
  - 2. It doesn't make sense to navigate to a destination's id before you even create it.
