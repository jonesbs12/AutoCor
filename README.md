# AutoCor

AutoCor is an addon for Final Fantasy XI (FFXI) Windower 4 that manages Corsair rolls.

## Project Status

This is a work in progress for personal use. You are free to use this project yourself. Feel free to contribute to this project by submitting pull requests or bug reports.

## Future Plans
- COR as a subjob support

## Installation

To install AutoCor, follow these steps:

1. Click the code dropdown. Download ZIP
2. Extract the files to your Windower 4 addons directory.
3. Add `autocor` to your Windower 4 script. lua load autocor

## Usage

Here are some example commands you can use with AutoCor:

Accepts auto-translate terms, not case-sensitive.
     `//cor [on|off]`
     `//cor roll <n> <job|roll_name>`  -- set roll
     `//cor cc [n|off]`                -- Use crooked cards on roll [n] (default is 1st roll, 0 is off)
     `//cor aoe <slot|party> [on|off]` -- Set party slots to monitor for aoe range.
     `//cor save`                      -- save settings on per character basis
     `//cor flip`                      -- Flip Roll 1 and Roll 2
        
    when setting rolls with commands it will check <job/roll_name> against the rolls job,
    next checks if a roll name is or begins with <job/roll_name>.
    
        [n] is roll order

        Examples:
        `//cor roll 1 war` or `//cor roll 1 fight` or `//cor roll 1 fighter's roll`
        
        `//cor roll 2 thf` or `//cor roll 1 rog` or `//cor roll 1 rogue's roll`

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.