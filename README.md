# Postman-Newman_APITesting
Second Assessment - Wizeline Workshop API Testing

Author - Daniel Espinosa

email - daes.ddl@gmail.com

---

Using the [Todoist API](https://developer.todoist.com/rest/v1/) complete the following Requests:

- Get active Tasks
- Create a new Task
- Update a Task
- Change a Task Status to Complete
- Reopen a Task
- Delete a Task

Adding at least the following positive tests:

- Status Codes
- Content
- JSON Schema
- Response Time

Every request should have at least a Negative Scenario.

---

#Executing Node Script:

Use the following Script to execute the API Test

    npm run testAPI
    
It will run the following Tests:

- ` CREATE `
  - ` Create new Task `
  - ` Negative Test: Create a new Task with no Body Content `
- ` GET `
  - ` Get active Task `
  - ` Negative Test: Get active Task from wrong URL `
  - ` Get an active Task `
  - ` Negative Test: Get an active Task from wrong ID `
- ` UPDATE `
  - ` Update a Task `
  - ` Negative Test: Update a Task with no Body Content `
  - ` Close a Task `
  - ` Negative Test: Close a Task Wrong URL `
  - ` Reopen a Task `
  - ` Negative Test: Reopen a Task Wrong ID `
- ` DELETE `
  - ` Delete a Task `
  - ` Negative Test: Delete a Task `
