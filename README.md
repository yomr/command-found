# command-found 
A programming quote instead of "command not found"


Add this to your .zshrc file (Haven't tested on other shells)

    function command_not_found_handler() {
      shuf -n 1 path/to/code_quotes
    }
    
Make sure you have shuf command. If you are on Mac OS X and you have coreutils installed, the shuf command will be available as `gshuf`. You could alias gsuf to shuf or replace shuf to gshuf in the above function.

Get the `code_quotes` file and  set the correct path.

Source the file!!

**Contribute by adding new quotes to the file!**
