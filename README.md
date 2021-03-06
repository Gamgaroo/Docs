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

### [com.gamgaroo.mvvm](https://github.com/Gamgaroo/com.gamgaroo.mvvm)

[![](https://img.shields.io/github/v/release/Gamgaroo/com.gamgaroo.mvvm?include_prereleases)](https://github.com/Gamgaroo/com.gamgaroo.mvvm/releases)
[![](https://img.shields.io/npm/v/com.gamgaroo.mvvm?label=MyGet&registry_uri=https://www.myget.org/F/gamgaroo/npm/)](https://www.myget.org/feed/gamgaroo/package/npm/com.gamgaroo.mvvm)
[![](https://img.shields.io/github/license/Gamgaroo/com.gamgaroo.mvvm.svg)](https://github.com/Gamgaroo/com.gamgaroo.mvvm/blob/master/LICENSE.md)

### [com.gamgaroo.reactive](https://github.com/Gamgaroo/com.gamgaroo.reactive)

[![](https://img.shields.io/github/v/release/Gamgaroo/com.gamgaroo.reactive?include_prereleases)](https://github.com/Gamgaroo/com.gamgaroo.reactive/releases)
[![](https://img.shields.io/npm/v/com.gamgaroo.reactive?label=MyGet&registry_uri=https://www.myget.org/F/gamgaroo/npm/)](https://www.myget.org/feed/gamgaroo/package/npm/com.gamgaroo.reactive)
[![](https://img.shields.io/github/license/Gamgaroo/com.gamgaroo.reactive.svg)](https://github.com/Gamgaroo/com.gamgaroo.reactive/blob/master/LICENSE.md)

### [com.gamgaroo.view](https://github.com/Gamgaroo/com.gamgaroo.view)

[![](https://img.shields.io/github/v/release/Gamgaroo/com.gamgaroo.view?include_prereleases)](https://github.com/Gamgaroo/com.gamgaroo.view/releases)
[![](https://img.shields.io/npm/v/com.gamgaroo.view?label=MyGet&registry_uri=https://www.myget.org/F/gamgaroo/npm/)](https://www.myget.org/feed/gamgaroo/package/npm/com.gamgaroo.view)
[![](https://img.shields.io/github/license/Gamgaroo/com.gamgaroo.view.svg)](https://github.com/Gamgaroo/com.gamgaroo.view/blob/master/LICENSE.md)
