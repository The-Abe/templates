# Templates

Jinja2 template files to use with the parser in bin/parse.

Just call `parse template.jinja output.ext` and it will ask you to fill in the
variables it finds in the template.

> Note:
> You must use the jinja2 variables in the output, or the parse script won't notice the variable.
> IE: Don't use variables only in conditionals or loops.
