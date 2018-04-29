# Django-ngcli
Django commands wrapper for angular-cli

# Installation

1. Put ngcli into apps folder of your projects

2. Add 'ngcli' to INSTALLED_APPS in settings.py

```python
INSTALLED_APPS = (
...
    'ngcli',
...
)

```

3. Set NG_SRC_PATH const in settings.py. For example:

```python
NG_SRC_PATH = os.path.join(BASE_DIR, 'website')
```

# How to use (examples)

1. Init sources (custom command)

```bash
$src/manage.py ng init
```

2. Generate class

```bash
$src/manage.py ng generate class supername
```

3. Build project (first set outDir in .angular-cli.json)

```bash
$src/manage.py ng build
```

4. Run developer server

```bash
$src/manage.py rungserve
```
