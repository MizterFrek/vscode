<h1 align="center">Laraphense</h1>

Lararvel Intelephense is code intelligence for productive [Laravel](https://laravel.com/) development.

# Features

-   [Show Suggestions based on the Laravel version](#show-suggestions-based-on-the-laravel-version)
-   [Auto-Completion](#auto-completion)
-   [Namespace Import, Expand and Sorting](#namespace-import-expand-and-sorting)
-   [Files Creation](#files-creation)
-   [Go to View (Blade File)](#go-to-view)
-   [Go to Component (PHP File)](#go-to-class)
-   [Env File Syntax Highlighting](#env-file-syntax-highlighting)
-   [Curly Braces Spacer](#curly-braces-spacer)

## Requirements

You Must have a workspace open having Laravel Installed.

### Show Suggestions based on the Laravel version

-   [Version History of Blade Directives](https://github.com/porifa/vscode-laraphense/blob/main/docs/BladeDirectives.md)
-   [Version History of Validation Rules](https://github.com/porifa/vscode-laraphense/blob/main/docs/ValidationRules.md)

### Auto-Completion

-   Suggests Blade Directives
-   Suggests Livewire Component
-   Suggests Route names and route parameters
-   Suggests Views and variables
-   Suggests Configs keys
-   Suggests Translations and translation parameters
-   Suggests Laravel mix function
-   Suggests Validation rules
-   Suggests View sections and stacks
-   Suggests Env Variables
-   Suggests Route Middlewares
-   Suggests Asset in the public directory

### Namespace Import, Expand and Sorting

-   Import a namespace by selecting a valid class name (from Command Platte, Context Menu or by pressing _ctrl+alt+i_)
-   Import all namespaces in the active file (from Command Platte, Context Menu or by pressing _ctrl+alt+a_)
-   Expand a namespace by selecting a valid class name (from Command Platte, Context Menu or by pressing _ctrl+alt+e_)
-   Sort imported namespaces in the active file (from Command Platte, Context Menu or by pressing _ctrl+alt+s_)
-   Generate namespace in the active file (from Command Platte, Context Menu or by pressing _ctrl+alt+g_)

### Files Creation

-   Create View (Blade) Files by selecting a valid string
-   Auto Suggest creating a view file if already doesn't exist

### Go To View

-   Go to view a blade file from blade and PHP files

### Go To Class

-   Go to view a PHP class file from blade and PHP files

### Env File Syntax Highlighting

-   Syntax Highlighting for environment files like (.env, .env.example)

### Curly Braces Spacer

-   Add Spaces between curly braces

## Extension Settings

These are the setting you can use.

### Customize the Maximum number of scanning rows

```json
"laraphense.maxLinesCount": 1000
```

default is 1000.

### Add Custom Validation Rules as an object

```json
"laraphense.customValidationRules": {}
```

for validation rule auto-completion.

### Add Models path as an array

```json
"laraphense.modelsPaths": ["app", "app/Models" ]
```

these 2 paths are included by default

### Customize view file extensions

```json
"laraphense.viewExtensions": [".blade.php", ".vue" ]
```

these 2 extensions are included by default

### Customize view folders paths

```json
"laraphense.viewFolders": {
                            "default": "/resources/views",
                            "js": "/resources/js/Pages",
                            "livewire": "/resources/views/livewire",
                            "vendor": "/resources/views/vendor"
                        }
```

these 3 extensions are included by default,

### Add View Directory Separator

```json
"laraphense.viewDirectorySeparator": "."
```

default is ".", you can use "/".

### Enable/Disable creating a view file from any valid string

```json
"laraphense.createViewEveryWhere": true
```

to enable or disable creating a view file from EveryWhere.

### Enable/Disable Go To View

```json
"laraphense.disableGoToView": false
```

If you want to disable the go-to view feature, set this to true.

### Enable/Disable Go To Config

```json
"laraphense.disableGoToConfig": false
```

If you want to disable the go-to config feature, set this to true.

### Enable/Disable Assets Auto-Completion

```json
"laraphense.disableAssetCompletion": false
```

If you want to disable assets autocomplete set this to true.

### Enable/Disable Livewire Auto-Completion

```json
"laraphense.disableLivewireCompletion": false
```

If you want to disable Livewire autocomplete set this to true.

### Enable/Disable Auth Auto-Completion

```json
"laraphense.disableAuthCompletion": false
```

If you want to disable auth autocomplete set this to true.

### Enable/Disable Blade Auto-Completion

```json
"laraphense.disableBladeCompletion": false
```

If you want to disable blade directives autocomplete set this to true.

### Enable/Disable Controller Auto-Completion

```json
"laraphense.disableControllerCompletion": false
```

If you want to disable Controller autocomplete set this to true.

### Enable/Disable Config Auto-Completion

```json
"laraphense.disableConfigCompletion": false
```

If you want to disable config autocomplete set this to true.

### Enable/Disable Curly Braces Spacer

```json
"laraphense.disableCurlyBracesSpacer": false
```

to enable or disable Curly Braces Spacer. By default, it is enabled

### Enable/Disable Eloquent Auto-Completion

```json
"laraphense.disableEloquentCompletion": false
```

If you want to disable Eloquent autocomplete set this to true.

### Enable/Disable Env Auto-Completion

```json
"laraphense.disableEnvCompletion": false
```

If you want to disable Env autocomplete set this to true.

### Enable/Disable Middleware Auto-Completion

```json
"laraphense.disableMiddlewareCompletion": false
```

If you want to disable Middleware autocomplete set this to true.

### Enable/Disable Mix Auto-Completion

```json
"laraphense.disableMixCompletion": false
```

If you want to disable Mix autocomplete set this to true.

### Enable/Disable Route Auto-Completion

```json
"laraphense.disableRouteCompletion": false
```

If you want to disable Route autocomplete set this to true.

### Enable/Disable Translation Auto-Completion

```json
"laraphense.disableTranslationCompletion": false
```

If you want to disable Translation autocomplete set this to true.

### Enable/Disable Validation Auto-Completion

```json
"laraphense.disableValidationCompletion": false
```

If you want to disable Validation autocomplete set this to true.

### Enable/Disable View Auto-Completion

```json
"laraphense.disableViewCompletion": false
```

If you want to disable View autocomplete set this to true.

### Enable/Disable Leading Namespace Separator for Expanding Namespace

```json
"laraphense.expandLeadingNamespaceSeparator": true
```

If you want to disable Expand class with a leading namespace separator then set this to false.

### Enable/Disable showing Message On Status Bar

```json
"laraphense.showMessageOnStatusBar": true
```

If you want to disable showing Message On Status Bar then set this to false.

### Enable/Disable auto Sort After Importing Namespace

```json
"laraphense.autoSortAfterImport": true
```

If you want to disable auto Sort After Import then set this to false.

### Enable/Disable Auto sort when a file is saved

```json
"laraphense.sortOnSave": false
```

If you want to enable Auto sort when a file is saved then set this to true.

# Advance Configurations

### Configure Regex for Matching view files

```json
"laraphense.viewRegex": "(?<=view\\(['\"]|.view:.?['\"]|View::make\\(['\"]|nest\\(['\"](https://github.com/porifa/vscode-laraphense/blob/HEAD/.*)['\"],.?['\"]|@include\\(['\"]|@extends\\(['\"]|@component\\(['\"]|@livewire\\(['\"]|Inertia::render\\(['\"]|\\(component:.['\"]|\\<)(\\<x-|\\<livewire:|[^'\" \\>]+)"
```

this regex is used to match the view files for quick jumping.

### Configure Regex for Creating view files

```json
"laraphense.viewCreateRegex": "(?<=View::make\\(['\"]|view\\(['\"]|.view:.['\"]|Inertia::render\\(['\"]|\\(component:.['\"])([^'\"]+)"
```

this regex is used to match the view files for auto-suggestion.

### Configure the PHP command like this

```json
"laraphense.phpCommand": "php -r \"{code}\""
```

this command is used to run PHP for indexing Laravel files.

### Exclude Namespaces

```json
"laraphense.excludeNamespaces": "**/node_modules/**"
```

Exclude glob pattern while finding files for namespaces.

### Configure the Base path like this

```json
"laraphense.basePath": "/core"
```

this Base path is used to read files.

### Configure the Code Base path like this

```json
"laraphense.basePathForCode": "/core/laravel"
```

This base path is used for require_once inside the PHP code.

<!-- ## Known Issues -->

## Credits

-   [PHP parser](https://github.com/glayzzle/php-parser)
-   [mkdirp](https://github.com/isaacs/node-mkdirp)

## Recommended extensions

-   [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)

**Enjoy!**
