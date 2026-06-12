# tudu
A simple command-line To Do List.  
I am under no illusion this is an indepth CLI app: This is meant as a simple, natural-to-use (and learn) utility and a coding practice for myself.  
  
## Commands
  
`add "Description"` - Add a to-do.  (Optionally `-i`nsert at line number)  
`list` - List all to-dos. (Optionally `-s`orted  or `-u`nchecked)  
`check <n>`  - Check a to-do off.  
`uncheck <n>` - Uncheck a to-do.  
`delete <n>` - Delete a to-do.  
`clean` - Remove all checked to-dos.  


## Issues:
- [x] Dim checked to-dos in default `see` list
- [ ] Remove/Check by Line Contents
- [x] ~~Single command to check/uncheck?~~ Not intuitive via text - scrapped!
- [x] Insert at specific point
- [x] List that sorts Unchecked above Checked
- [ ] Add a confirm step before `clean`
- [ ] Simple marker for Priority tasks with !, possibly. Probably not.
- [ ] New command to `swap` two to-dos by their number
