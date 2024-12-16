# FastAPI Snippets Extension

Welcome to the FastAPI Snippets Extension for Visual Studio Code! This extension provides handy code snippets for FastAPI, making it easier to scaffold routes quickly and efficiently in your Python projects.

## Features

This extension includes snippets for creating FastAPI routes at both the application level and the router level. The available snippets are:

### App-level routes

- `fs-get`: Scaffold a GET route.
- `fs-post`: Scaffold a POST route.
- `fs-put`: Scaffold a PUT route.
- `fs-delete`: Scaffold a DELETE route.

### Router-level routes

- `fs-router-get`: Scaffold a GET route in a router.
- `fs-router-post`: Scaffold a POST route in a router.
- `fs-router-put`: Scaffold a PUT route in a router.
- `fs-router-delete`: Scaffold a DELETE route in a router.

### Usage

#### App-level GET route

To create a GET route at the app level:

```python
@app.get("/path")
def method(request):
    pass
```

### Router-level POST route

To create a POST route in a router:

```python
@router.post("/path")
def method(request):
    pass
```

Simply type the prefix (e.g., fastapi-app-get) and the corresponding snippet will be inserted. Use Tab to navigate through the placeholders and fill in the details.

### Requirements

There are no special requirements or dependencies for this extension. Just install it and start using the snippets in your Python files.
Extension Settings

This extension does not add any VS Code settings.

### Known Issues

There are no known issues at this time. If you encounter any problems, please report them on the GitHub [issues page](https://github.com/Likhith-18/fastapi-vscode-extension/issues).
Release Notes
1.0.0

    Initial release of FastAPI Snippets Extension.
    Added snippets for GET, POST, PUT, and DELETE routes at both the app level and router level.
