# Windows CMD.exe Utils

This repository includes a set of useful command-line programs I made for Windows.

**mf.exe** *[Miker Find]* - A recursive find util with PCRE goodness built in.

- --file  = Show files only.
- --dir   = Show directories only.
- --help  = This dialogue.
- --regex "<REGEX>" = Regex filter.

**mrep.exe** *[Miker Regex Print]* - Grep but better? 

- <STDIN> | mrep.exe --regex "<PATTERN>" <FILE(S)>

**murl.exe** *[Miker URL]* - Frontend for curl.

- --url "<URL>"
- --url "<URL>" --regex "<REGEX>"
- --url "<URL>" --regex "<REGEX>" --links
- --url "<URL>" --readable
- --url "<URL>" --readable --regex "<REGEX>"
- --url "<URL>" --email
- --url "<URL>" --xpath "<XPATH>"
- --url "<URL>" --save
- --url "<URL>" --saveas "<FILE>"
- --url "<URL>" --info
- --url "<URL>" --info --regex
- *NOTE: You can add --cookie <COOKIE-FILE> to all options.*
- *NOTE: Use --help to learn about the options.*