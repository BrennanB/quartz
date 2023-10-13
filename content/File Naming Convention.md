
# Rules

- When you create a part or assembly, immediately save it, following the naming convention and putting it in the correct folder to avoid complications and issues later on
- It will take some getting used to, but stick to it and use this as a reference!
- Convention: ”###-###-## insert descriptive name”
- The first 3 digits indicate the assembly (top-level, sub-assembly, sub-sub-assembly)
- The next 3 digits indicate a unique part number (so the first part made for that assembly is 001)
- The last 2 digits indicate the configuration of a part, since it is the same file but a different physical part (if there is no configuration, it is left as 00)
- We have a new parts library, with prefixes to indicate the category of the part
- H-###-### for hardware (eg. Fasteners)
- EP-###-###-## for electrical and pneumatic parts (eg. Radio, piston, compressor)
- O-###-###-## for off the shelf parts
- MP-###-###-## for motion and power transmission (eg. Bearings, wheels
- There are two categories we use for inventory only, just to keep track of what we have in stock
- M-###-### for materials (eg. Lexan, plywood, acrylic)
- T-###-### for tools

## Example: Lexan arm on the Charlie’s cargo intake

Theoretical breakdown:

- “000-000-00 Charlie” is the full robot
- “200-000-00 Elevator” is the top assembly
- Where 100-000-00 is the Drivetrain
- “130-000-00 Cargo Intake” is the sub-assembly
- Where 110-000-00 is the First Elevator Stage and 120-000-00 is the Second Elevator Stage ^6658f8
- The cargo intake is not in a further sub assembly, so the third digit is 0!
- “130-001-00 Cargo Intake Arm” is the part, with no configurations
  

![](https://lh6.googleusercontent.com/N9IwBsTdyLTFGuZ5FYNGl9DMnsqTMtU8Q73mQxQfIv4xWtO8Bbs24kfesgESeqiXkzxVDa2RPNo_tixIudjvaIOdxfnwp1HmPba_8La_spKooOUOX-RDyC8ihd19OeNYJz4GuoVd4opjSWCtl1cFjQ)
