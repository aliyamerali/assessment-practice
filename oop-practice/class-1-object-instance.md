## class Classroom instance

### Room #101

#### Attributes:
```ruby
desk_count = 30  
classes_taught = {"Period 1": "English", "Period 2": "Spanish", "Period 3": "Math"}  
board_type = "dry erase"
in_use = false
```


#### Methods:

| Method run    | Outcome  |
| ------------- |:----------------|
|`add_desk` | `desk_count = 31`  |
|`period_start` | `in_use = true`  |
|`upgrade_classroom` | `board_type = "smart"`  |
|`add_class("Period 5", "Physics")` | `classes_taught = {"Period 1": "English", "Period 2": "Spanish", "Period 3": "Math", "Period 5": "Physics"}`|
