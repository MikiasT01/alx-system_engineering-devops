# 0x03-shell_variables_expansions

## 0-alias
This script defines an alias for the command `ls` that executes `rm *`, which deletes all files in the current directory. To use it, source the script with `source ./0-alias`. After sourcing, typing `ls` will remove all files. Use `\ls` to bypass the alias and list directory contents instead. **Caution**: This alias is dangerous and should not be used in a production environment as it deletes files without confirmation.
