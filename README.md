# ucph-handout - Unofficial LaTeX document class for University of Copenhagen handouts
`ucph-handout` is an unofficial LaTeX document class for producing
handouts with University of Copenhagen logo.

## Example
![Example Worksheet](/examples/example.png | width=250)

## Installation
There are three steps to installation:
 1. Clone or download the repository to your local machine

 2. Move or symlink the directory `ucph-handout` inside your
   `texmf/tex/latex/` directory.

   The `texmf/tex/latex` directory location depends on your OS:
     - Windows 10 (w. Miktek): `C:\Users\<user name>\Appdata\Local\MikTex\<number>\tex\latex\`
     - Windows Vista/7 `C:\Users\<user name>\texmf\tex\latex\`
     - Windows XP `C:\Documents and Settings\<user name>\texmf\tex\latex\`
     - Linux `~/texmf/tex/latex/`
     - Mac OS X `/Users/<user name>/Library/texmf/tex/latex/`

 3. Open a command prompt and type `texhash`. The command updates the
   database of installed LaTeX packages and documentclasses.

If you have any problems, refer to the answers in the following TeX
StackExchange post:
https://tex.stackexchange.com/questions/1137/where-do-i-place-my-own-sty-or-cls-files-to-make-them-available-to-all-my-te/

## Contributing
Feedback, contributions and ideas are welcome. Don't hesitate to send
pull-requests, report issues or give feedback directly to Martin
Dybdal (dybber@di.ku.dk)

## License
The documentclass is released under the MIT License. See LICENSE.
