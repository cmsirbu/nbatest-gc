# Installing the App in Nautobot

## Prerequisites

- The plugin is compatible with Nautobot 1.2.0 and higher.
- Databases supported: PostgreSQL, MySQL

## Install Guide

```{admonition} Developer Note - Remove Me!
Detailed instructions on installing the App.
```

The plugin is available as a Python package via PyPI and can be installed with `pip`:

```shell
pip install nautobot-golden-config
```

To ensure Nautobot Golden Configuration is automatically re-installed during future upgrades, create a file named `local_requirements.txt` (if not already existing) in the Nautobot root directory (alongside `requirements.txt`) and list the `nautobot-golden-config` package:

```no-highlight
# echo nautobot-golden-config >> local_requirements.txt
```

Once installed, the plugin needs to be enabled in your `nautobot_config.py`

```python
# In your nautobot_config.py
PLUGINS = ["nautobot_golden_config"]

# PLUGINS_CONFIG = {
#   "nautobot_golden_config": {
#     ADD YOUR SETTINGS HERE
#   }
# }
```

### Access Requirements

```{admonition} Developer Note - Remove Me!
What external systems (if any) it needs access to in order to work.
```

## App Configuration

```{admonition} Developer Note - Remove Me!
Any configuration required to get the App set up.
```
