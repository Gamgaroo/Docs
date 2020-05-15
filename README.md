# Docs

Unity Package Manager [Scoped Registry](https://docs.unity3d.com/Manual/upm-scoped.html):

```json
"scopedRegistries": [
    {
        "name": "Gamgaroo",
        "url": "https://www.myget.org/F/gamgaroo/npm/",
        "scopes": [
            "com.gamgaroo"
        ]
    }
]
```

or

```json
"scopedRegistries": [
    {
        "name": "Gamgaroo",
        "url": "https://pkgs.dev.azure.com/gamgaroo/Packages/_packaging/gamgaroo/npm/registry/",
        "scopes": [
            "com.gamgaroo"
        ]
    }
]
```
