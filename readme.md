## Specifications (CATEGORIES)
| Test# | Behavior | Input Example |  Output Example  |
| ----- | -------- |:-------------:|:----------------:|
| Task1 | Empty Database is empty | nothing! | GetAll().Count = 0 |
| Task2 | Two categories with same name are equal (requires override) | "Chores", "Chores" | true |
| Task3 | Successfully saves category (.Save()/.GetAll()) | "Chores" | true |
| Task4 | Assigns ID to Category Object (.Save()/.GetAll()/.GetId()) | "Chores" | true (0,0) |
| Task5 | Finds category in DB (.Save()/.GetId()/.Find()) | "Chores" | true |
| Cat1 | Empty Database is empty | nothing! | GetAll().Count = 0 |
| Cat2 | Two categories with same name are equal (requires override) | "Chores", "Chores" | true |
| Cat3 | Successfully saves category (.Save()/.GetAll()) | "Chores" | true |
| Cat4 | Assigns ID to Category Object (.Save()/.GetAll()/.GetId()) | "Chores" | true (0,0) |
| Cat5 | Finds category in DB (.Save()/.GetId()/.Find()) | "Chores" | true |
| Cat6 | Retrieves all tasks with categories (.Save()/.GetId()/.GetTasks()) | "Chores" | "Laundry, dishes, etc..." |
| Cat7 | Update category in DB | "Work Chores" | "Category Updated to Work Chores" |
| Cat8 | Delete category from DB | Delete category | Category Deleted |
