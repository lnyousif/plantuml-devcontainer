# Dev Container PlantUML:
This template allows you to run the Diagraming Tool PlantUML Server inside your dev container and generate all your diagrames internally without the need to use the public server.

After opening the dev container you can preview any diagram .puml by using the preinstalled Plantuml extension that is linked to a PlantUml Server running inside a container within the Dev Container. 



### Options


```jsonc
{
    // ...
    "options": {
        "exportFormat": {
            "type": "string",
            "description": "Choose your exportFormat.",
            "proposals": [
                "png", "svg", "eps", "pdf", "vdx", "xmi", "scxml", "html", "txt", "utxt", "latex", "latex:nopreamble"
            ],
            "default": "png"
        },
        "diagramsSource": {
            "type": "string",
            "description": "Choose your diagrams source folder",
            "default": "diagrams/src"
        },
        "diagramsOutDir": {
            "type": "string",
            "description": "Choose your renderd diagrams output folder",
            "default": "diagrams/out"
        }
    }
}
```
