# CO-LAB — Project Manager

JavaFX desktop application for lightweight team project tracking.  
Built as a university group project.

## Tech Stack

- Java 11  
- JavaFX 13  
- Maven  
- JSON-simple  

## Features

- User authentication  
- Project creation and editing  
- Task management with assignees  
- Sub-tasks and threaded comments  
- Per-task history tracking  
- Kanban-style column organization (ToDo / Doing / Completed)  

## Run Locally

From the `ui/` directory:

```bash
ln -s . ui
mvn javafx:run
```

> Note: Due to the original team project structure, a symlink is required for local execution.

## Demo Credentials

- aMadden / 1234  
- jBlum / password  

## Status

Functional prototype with local JSON persistence.  
Core flows are implemented; additional refinement would be required for production use.
