### Set up PostgreSQL using Docker:

1. Check if Docker is installed and running.
2. Start a PostgreSQL container named `sql12_cc` with password `postgres` and port `5433`.
3. Connect to PostgreSQL.
4. Create a database named `test_ecom_db`.
5. Execute the required commands and verify everything works.

### Backend
1. Use Go best practices and format code with `gofmt`
2. Keep code simple, readable, and organized.
3. Separate HTTP handlers, business logic, and database operations where needed.
4. Connect to PostgreSQL and create the required tables.
5. Enable CORS for the React development server.


### Frontend
1. Use functional components and React Hooks.
2. Use `useState` for local state and `useEffect` only when needed.
3. Keep components and API calls organized.
4. Avoid unnecessary state and re-renders.
5. Use unique keys for lists.
6. Handle loading, error, empty, and success states.
7. Follow React best practices and write clean, reusable code.


### Verify
Run the backend, the frontend and the tests, and confirm everything works end to end. To test install extension claude code extension