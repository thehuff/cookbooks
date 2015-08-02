# Sublime Text - Projects

## Configure a project, general

Refer to <https://www.sublimetext.com/docs/3/projects.html>.

## Configure a project, Rails

`project.sublime-project`:

```json
{
  "folders": [
    {
      "path": ".",
      "folder_exclude_patterns": [
        "tmp",
        "vendor",
        "log"
      ]
    }
  ],
  "settings": {
  },
  "build_systems": [
  ]
}
```
