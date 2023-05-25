# Task Tracker

Small App that allows to add and delete tasks.
It's my first project using React. It also includes a mock Backend with JSON Server.




## Installation

1. Clone the repository:

```bash
 git clone https://github.com/FERLUI01/react-task.git

```
    
2. Instal the dependencies:

```bash
 cd react-task
 npm install
```
3. Start the mock JSON Server (http://localhost:5000):

```bash
 npm run server
```

This will start the JSON Server and use the db.json file as the mock database for the task tracker.


4. Start the development server (http://localhost:3000):

```bash
    npm start
```

## Usage

To use the task tracker follow these steps:

1. Open your web browser and navigate to http://localhost:3000.

2. You can add new tasks by clicking the ADD button, toggle exisiting tasks to have the reminder on/off and you can delete existing tasks.

3. The task tracker is connected to the mock JSON Server, which simulates a backend API. The mock data is stored in the db.json file. Any changes you make in the task tracker will be reflected in the mock database.

Note: Since this is a mock server, the data will not persist across server restarts.




## Tech Stack

**Client:** React

**Server:** JSON-Server