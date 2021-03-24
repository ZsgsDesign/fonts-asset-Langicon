# fonts-asset-Langicon
Langicon for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/langicon
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/langicon/langicon.css">
```

## Credit

[ZsgsDesign](https://github.com/ZsgsDesign)