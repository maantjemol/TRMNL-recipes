# TRMNL Plugins

This repository contains plugins my recipes for [TRMNL](https://usetrmnl.com/). The plugins currently include:

- **Wave heights**: Shows wave height data and sunrise/sunset information
- **Planning Center**: Displays upcoming services from Planning Center

## Getting Started

### Prerequisites

You'll need to install **trmnlp** to run the plugins locally and push them to your TRMNL instance:

```
gem install trmnl_preview
```

### Running a Plugin

Go into the plugin directory and run the following command to start the development server:

```bash
trmnlp serve
```

This will start a local server where you can preview the plugin in TRMNL.

If you want to use the plugin on your TRMNL instance, you can run:

```bash
trmnlp login
trmnlp push
```

### Plugin Structure

Each plugin follows this structure:

- settings.yml: Plugin settings including custom fields
- `src/*.liquid`: Template files for different layouts

## Customizing Plugins

To customize a plugin:

1. Modify the liquid templates in the `src` directory
2. Adjust settings in settings.yml

## More Information

For more details on developing plugins for TRMNL, visit the [trmnlp documentation](https://github.com/usetrmnl/trmnlp).
