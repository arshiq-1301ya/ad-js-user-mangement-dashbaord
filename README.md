# User Management Dashboard Using REST APIs

## Project files
- `index.html` — complete assignment in one file (HTML, CSS and JavaScript).

## How to run
1. Extract the ZIP file.
2. Open the `User-Management-Dashboard` folder in VS Code.
3. Open `index.html`.
4. Right-click the file and choose **Open with Live Server** (if Live Server is installed), or open the file in Chrome.
5. Keep an internet connection active because the project uses JSONPlaceholder API.

## How to test
- On page load, the dashboard sends a GET request and displays users.
- Click **Add New User (POST)** to add John Doe.
- Click **Update Email** beside the first user to update the email.
- Click **Delete** beside any user to remove that user from the page.

## Network tab verification
1. Press `F12` in Chrome.
2. Open the **Network** tab.
3. Select **Fetch/XHR**.
4. Perform each operation and inspect its request method, status and payload.

Expected methods/statuses:
- GET — 200
- POST — 201
- PUT — 200
- DELETE — 200

## Important API note
JSONPlaceholder is a testing API. POST, PUT and DELETE responses are simulated; the server does not permanently save these changes. The project updates the page locally after a successful response. Refreshing the page loads the original users again.
