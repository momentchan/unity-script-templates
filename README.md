# Unity Script Templates

## Script Templates submodules

```
git submodule add https://github.com/momentchan/unity-script-templates.git Assets/ScriptTemplates
```

## Script Templates naming

You can see that all the template scripts files have a specific naming syntax :

git add
85-Other Scripts__Scriptable Object-MyClass.cs.txt
```

Let's see the composition of that... thing :

| 85 | Other Scripts | Scriptable Object | MyClass | .cs |
| - | - | - | - | - |
| Menu position | Menu name | Submenu name | Default name of the new created file | Created file extension |

Note that submenus are facultative, but you can setup as many submenus as you want, by separating elements with "`__`".

## Script Template content

You can make script templates of any text asset you want (it can be C#, JSON, XML, YAML, TXT, or any code or text content).

Inside these scripts, you can also use `#SCRIPTNAME#` keyword. When Unity generates the new asset, it will replace that keyword by the created file name. It can be useful for automating class name generation.
