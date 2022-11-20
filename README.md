# GD-Bugs

This is a database containing known bugs and their fixes for the popular indie game called "Geometry Dash"  
The database is for a project on [My Website](https://wyliemaster.github.io/projects/bugs/)

## Want to contribute?

Contributers are always welcome. You just need to follow the format and then create a pull request

create a file that describes the bug. for this example it will be called `bug_name.gdp`

> the `.gdp` file extension is important so dont forget it!

Inside the file, enter the following

```html
<!--bug_name.gdp-->
[TITLE]
  This will be the title that displays on the page
[/TITLE] <!-- Required -->

[DESC]
  This will be a brief description of the bug
[/DESC] <!-- Required -->

[FIX]
  This will be an explanation on how to fix the bug if there is a fix. 
  If there is no fix then don't add this
[/FIX] <!-- Optional -->

[DETAILS]
  This will include a technical explanation into how the bug is implemented for nerds. 
  Most contributers won't know so don't use this
[/DETAILS] <!-- Optional -->
```

Once you have finished the file, put it inside of the `bugs/` directory.

### Issues

If you know of a bug but don't know enough about it to contribute directly, you can submit an [Issue](https://github.com/Wyliemaster/GD-Bugs/issues) detailing what you know and other contributers can investigate and then add it to the database
