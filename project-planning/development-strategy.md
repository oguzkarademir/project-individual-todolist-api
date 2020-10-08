# Development Strategy

> `Asyncronous week 3`

## todo-list-with-API

### WIREFRAME

![wireframe](/wireframe-1.png)

---

## 0. Set-Up

_A User can see my initial repository and live demo_

### Repository

- Created a new repository to fork from this [repository](https://github.com/HackYourFutureBelgium/restful-pjs)
- Cloned the repository
- Added a wireframe
- Started the development strategy
- Pushed the changes to GitHub
- Turned on GitHub Pages

---

## 1. Initialize Application

__As a user I want to see the initial page when I load the site__

### REPO

- This user story is developed on branch `master`.

### Task A

- Create HTML

### Task B

- Create CSS style

---

## 2. Development Strategy

### REPO

- This user story is developed on branch `master`.

### Task A

- Completed development strategy with all task

---

## 2. Display

__As a user, when I click buttons, I want to see the changing of user interface__

### REPO

- This user story is developed on branch `display`.

### Task A

- Create a render method in class object
- Create a display handler with click event
- Use render method in display handler
- Print the information in the database to the user interface with 'fetch' every time I press buttons.
- Use async-await

---

## 3. Add Button 

__As a user, when I click the Add button, the information of the item in the database should be deleted.__

### REPO

- This user story is developed on branch `Add`.
- This branch is merged to `master` branch after completion.

### Task A

- Using fetch 'POST' method to save the information entered by the user into the database

---

## 4. Delete Button

__As a user, when I click the Delete button on item, the information I entered must be saved in the database.__

### REPO

- This user story is developed on branch `Delete`.
- This branch is merged to `master` branch after completion.

### Task A

- Using fetch 'DELETE' method to delete the information that the user wants to delete

---

## 5. Checkbox

__As a user, when I click the checkbox button on item, `completed` key in `db.sjon` change.__

### REPO

- This user story is developed on branch `Checkbox`.
- This branch is merged to `master` branch after completion.

### Task A

- Using fetch 'PUT' method to update the situation of checkbox in database

---

## 6. Finish

### REPO

- This user story is developed on branch `finish`.
- This branch is merged to `master` branch after completion.

### Task A

- Checking HTML-CSS-JS validate situation
- Fix bugs