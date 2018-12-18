# Dainty for Visual Studio Code

Dainty is a **color theme generator** with support for **Visual Studio Code**. It comes with default presets **Dainty Dark** and **Dainty Light** as well as **popular color themes** as its presets.

## Features

- Colors are processed, and can be adjusted, within the Lab color space
- Punctuation marks are slightly dimmed
- Workbench is less busy than in the default/original themes

## Presets

### Dainty Dark (`dainty-dark`)

![Dainty Dark](assets/vscode-dainty-dark.png)

### Dainty Light (`dainty-light`)

![Dainty Light](assets/vscode-dainty-light.png)

### Cobalt2 (`cobalt2`)

![Cobalt2](assets/vscode-cobalt2.png)

### Dracula (`dracula`)

![Dracula](assets/vscode-dracula.png)

### Night Owl (`night-owl`)

![Night Owl](assets/vscode-night-owl.png)

### One Dark Pro (`one-dark-pro`)

![One Dark Pro](assets/vscode-one-dark-pro.png)

### Material Theme Palenight (`palenight`)

![Material Theme Palenight](assets/vscode-material-theme-palenight.png)

### Prettier (`prettier`)

![Prettier](assets/vscode-prettier.png)

## Additional presets

- Ayu Mirage (`ayu-mirage`)
- Dainty Dark Minimal (`dainty-dark-minimal`)
- Dark+ (`dark-plus`)
- Fluent (`fluent`)
- Material Theme Ocean (`material-theme-ocean`)
- Material Theme (`material-theme`)
- Minimal (`minimal`)
- Monokai Night (`monokai-night`)
- Monokai (`monokai`)
- Oceanic Next (`oceanic-next`)
- Purple Haze (`purple-haze`)
- Snazzy Theme (`snazzy-theme`)
- Tomorrow Night Eighties (`tomorrow-night-eighties`)

## Get it

The easiest way to get Dainty is to install it through **Extensions in Visual Studio Code**. Search for “dainty”.

## Build it

    git clone https://github.com/alexanderte/dainty-vscode.git
    cd dainty-vscode
    yarn

### Install theme into your `settings.json`

    yarn build -i -p dainty-dark

### Configuration

See https://dainty.site/configuration for more information.

#### VS Code-specific customization

It is possible to tap into the customization done by Dainty through the objects `__colors` and `__tokenColors`.

    {
      "customizations": {
        "__colors": {
          "activityBar.background": "neutral-2"
        },
        "__tokenColors": [
          {
            "scope": ["string"],
            "foreground": "blue-14"
          }
        ]
      }
    }

## License

Dainty is licensed under the [MIT License](https://github.com/alexanderte/dainty-vscode/blob/master/license.md).
