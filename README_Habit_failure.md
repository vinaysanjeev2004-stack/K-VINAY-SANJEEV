# Daily Habit Failure Tracker

## What is this project?

This is a **reverse habit tracker** — instead of pretending you’re perfect and logging only your good days, this project focuses on the moments where things *actually* go wrong.

The idea is simple: when you mess up, you write it down.

That might sound uncomfortable, but it’s surprisingly effective. When you consistently log failures like *stress eating*, *doom-scrolling*, or *procrastinating*, patterns start showing up. And once patterns are visible, they’re harder to ignore — and easier to fix.

This project isn’t about guilt. It’s about awareness.


## What does it do?

- Log habit failures with intensity, triggers, and notes  
- View all logged failures honestly  
- Search for repeating habits  
- Analyze statistics and patterns  
- Delete records if required  
- Automatically save all data  



## Why I built this

This project was created for a **Python mini-project assignment**, but the goal was to build something meaningful instead of a routine or recycled idea.

Tracking failures reveals more about behavior than tracking success. This tool helps convert awareness into improvement.



## Technical details (for evaluation)

### Data structures
- List: `failure_records`
- Dictionary per record:
  `id`, `habit`, `intensity`, `trigger`, `notes`, `date`, `time`
- Structure: list of dictionaries

### Functions
1. load_data_from_file()
2. save_data_to_file()
3. add_failure_record()
4. view_all_failures()
5. search_failures()
6. view_statistics()
7. delete_failure()
8. display_menu()
9. main()

### Control flow
- while loop for menu
- if/elif/else for decisions
- for loops for iteration

### Methods used
**List:** append(), pop(), list comprehensions  
**Dictionary:** get(), items(), keys()  
**String:** strip(), lower(), title(), capitalize(), f-strings  

### Error handling
- Missing file handling
- Corrupt JSON handling
- Invalid input handling
- File I/O exceptions

### File handling
- Uses `with open()`
- Stores data in `failure_data.json`
- Uses json.load() and json.dump()

### Other concepts
- datetime module
- lambda functions
- enumerate()

---

## How to run

1. Install Python 3.6+
2. Save file as `habit_tracker.py`
3. Place `failure_data.json` (optional) in same folder
4. Open terminal
5. Navigate to folder
6. Run:
   python habit_tracker.py

Name : 
USN:
College: 
