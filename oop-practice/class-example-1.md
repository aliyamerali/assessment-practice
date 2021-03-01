## Classes that may exist in a school

### class Classroom

#### Attributes:

| Attribute       | Data Type     |
| -------------   |:-------------:|
| desk_count      | integer       |
| classes_taught  | array         |  
| board_type      | string        |   
| in_use          | boolean       |   

#### Methods:
| Method        | What it does     |
| ------------- |:----------------:|
| add_desk      | desk_count is increased by 1  |
| period_start  | in_use set to true            |  
| upgrade_room  | board_type is set to "smart"  |   
| add_class()   | new class appended to classes_taught  |   
