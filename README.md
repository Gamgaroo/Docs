# Documentation

## Installation

It is recommended to use [UPM Scoped Registry](https://docs.unity3d.com/Manual/upm-scoped.html) to auto-resolve dependencies and see updates in Unity Package Manager when they are available.

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

However, it is also possible to manually install packages using [UPM Git](https://docs.unity3d.com/Manual/upm-git.html) method. In this case you must manually install all dependencies in the project.

## Versioning

All packages use [Semantic Versioning](https://semver.org/).

> ⚠️ Major version zero is all about rapid development. This kind of packages [MAY](https://semver.org/#doesnt-this-discourage-rapid-development-and-fast-iteration) introduce breaking changes on the Minor version updates. Keep this in mind if you intend to use such packages.

## Package List

### [Gamgaroo/Reactive](https://github.com/Gamgaroo/Reactive)

[![](https://img.shields.io/github/v/release/Gamgaroo/Reactive?include_prereleases)](https://github.com/Gamgaroo/Reactive/releases)
[![](https://img.shields.io/npm/v/com.gamgaroo.reactive?label=MyGet&registry_uri=https://www.myget.org/F/gamgaroo/npm/)](https://www.myget.org/feed/gamgaroo/package/npm/com.gamgaroo.reactive)
[![](https://img.shields.io/github/license/Gamgaroo/Reactive.svg)](https://github.com/Gamgaroo/Reactive/blob/master/LICENSE.md)

### [Gamgaroo/MVVM](https://github.com/Gamgaroo/MVVM)

[![](https://img.shields.io/github/v/release/Gamgaroo/MVVM?include_prereleases)](https://github.com/Gamgaroo/MVVM/releases)
[![](https://img.shields.io/npm/v/com.gamgaroo.mvvm?label=MyGet&registry_uri=https://www.myget.org/F/gamgaroo/npm/)](https://www.myget.org/feed/gamgaroo/package/npm/com.gamgaroo.mvvm)
[![](https://img.shields.io/github/license/Gamgaroo/MVVM.svg)](https://github.com/Gamgaroo/MVVM/blob/master/LICENSE.md)
