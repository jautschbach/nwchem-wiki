## TITLE

Specify job title.

This top-level directive allows the user to identify a job or series of
jobs that use a particular database. It is an optional directive, and if
omitted, the character string containing the input title will be empty.
Multiple TITLE directives may appear in the input file (e.g., the [water
example
file](Getting-Started#water-molecule-sample-input-file)) in
which case a task will use the one most recently specified. The format
for the directive is as follows:

`TITLE `<string title>

The character string

<title>

is assigned to the contents of the string following the TITLE directive.
If the string contains white space, it must be surrounded by double
quotes. For example,

`title "This is the title of my NWChem job"`

The title is stored in the database and will be used in all subsequent
tasks/jobs until redefined in the input.
