Express - Mongoose - Cors
The application is now running locally on http://localhost:3000/.

## API Endpoints

The following API endpoints are available:

- `POST /tasks`: Create a new task. Send a JSON object in the request body with `description` and `completed` fields.
- `GET /tasks`: Get a list of all tasks.
- `PATCH /tasks/:id`: Update a task by ID. Send a JSON object in the request body with `description` and/or `completed` fields to update.
- `DELETE /tasks/:id`: Delete a task by ID.
