# Shell, I/O Redirections and filters

## I/O Redirections
   - Redirection is a feature in Linux such that you can change the standard input/output devices when executing a command.
      * READ MORE [Shell I/O Redirection, The Shell Filters and Shell Expansion](https://dev.to/labank_/shell-io-redirection-the-shell-filters-and-shell-expansion-3a9p).  

 

## Special characters
   `"  "` whitespace -  this is a tab, newline, vertical tab,  -> bash uses whitespace to determine where words begin and end.
   - ` $` Expansion 
	  * Parameter expansion ($var, or ${var}.
	  * Command substitution $(command)
	  * Arithmetic expansion $((89+34)).
   - `‘ ‘` Single quotes  protect the text inside them so that it has a literal meaning.
   - `""`  Double quotes — protect the text inside them from being split into multiple words or arguments.
   - ` \`  Escape (backslash) prevents the next character from being interpreted as a special character.
   - `# `  Comment ---  the # character begins a commentary that extends to the end of the line. Comments are notes of explanation and are not processed by the shell.
   - `(())`  Arithmetic expression — with an arithmetic expression, characters such as +, -, *, and / are mathematical operators used for calculations. They can be used for variable assignments like (( a = 1 + 4 )) as well as tests like if (( a < b )).
    
   - ` $(()) `  Arithmetic expansion — Comparable to the above, but the expression is replaced with the result of its arithmetic evaluation. Example: echo "The average is $(( (a+b)/2 ))".
   -  ` *, ?`  Globs wildcard" characters which match parts of filenames (e.g. ls *.txt).

