## Clarifications

- Step 0
  - Instructions don't specify whether to call `npm init -y` in the `server` directory specifically or just the root. If not done in the correct directory, `npm run start` will not work properly.
- Step 3
  - Reset script will not work correctly due to foreign key dependencies between `activities` and `trips`. Dropping `trips` fails while `activities` still exists.
  - This also affects the `DELETE` on an existing trip.
