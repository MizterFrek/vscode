# Change Log

## [Unreleased]

-   Livewire Full Support
-   Blade Language Server in the [Laraphense](https://marketplace.visualstudio.com/items?itemName=Porifa.laraphense)

## [1.25.0 - 2023-12-25]

### `Added`

-   [Feat#90](https://github.com/porifa/vscode-laraphense/issues/90): Add session blade Directive
-   [Feat#89](https://github.com/porifa/vscode-laraphense/issues/89): Add use Blade directive

## [1.24.2 - 2023-12-01]

### `Added`

-   [Feat#88](https://github.com/porifa/vscode-laraphense/issues/88): Add Hex Color Validation Rule
-   [Feat#87](https://github.com/porifa/vscode-laraphense/issues/87): Add `pushElseIf` and `pushElse` blade directives
-   [Feat#86](https://github.com/porifa/vscode-laraphense/issues/86): Adds more implicit validation rules for present
-   [Feat#36](https://github.com/porifa/vscode-laraphense/issues/36): Added parameters to the timezone validation rule

## [1.24.1 - 2023-08-21]

### `Fixed`

-   [Bug#43](https://github.com/porifa/vscode-laraphense/issues/43): Error in generating Namespace for the file
-   [Bug#42](https://github.com/porifa/vscode-laraphense/issues/42): Curly Braces Spacer throws exception
-   Change Extension config Name case from `Laraphense` to `laraphense`

## [1.24.0 - 2023-08-18]

### `Added`

-   Added Namespace Import, Expand and Sorting Features

## [1.23.2 - 2023-08-16]

### `Changed`

-   Changed some internal for livewire support

## [1.23.1 - 2023-08-15]

### `Changed`

-   Updated Documentation of Blade Directives and Validation Rules

## [1.23.0 - 2023-08-13]

### `Added`

-   Add Documentation of Blade Directives and Validation Rules

## [1.22.0 - 2023-04-29]

### `Added`

-   Change Extension Name from `Laravel Intelephense` to `Laraphense`
-   Go to Component Class

## [1.21.0 - 2023-03-25]

### `Added`

-   Added Go to Livewire Component Class
-   Added Livewire Completion for `@livewire` directive

## [1.20.6 - 2023-03-18]

### `Added`

-   Added [style blade directive](https://github.com/porifa/vscode-laraphense/pull/31) for laravel version `9.50.0`
-   Added [missing validation rules](https://github.com/porifa/vscode-laraphense/pull/30) for laravel version `9.49.0`

### `Updated`

-   Updated `required` blade directive for laravel version `9.20.0`
-   Updated `js` blade directive for laravel version `8.71.0`
-   Updated `aware` blade directive for laravel version `8.64.0`
-   Updated `class` blade directive for laravel version `8.51.0`
-   Updated `sectionMissing` blade directive for laravel version `7.22.0`
-   Updated `production` blade directive for laravel version `7.11.0`
-   Updated `env` blade directive for laravel version `7.11.0`
-   Updated `includeUnless` blade directive for laravel version `6.5.1`
-   Updated `endcomponentFirst` blade directive for laravel version `5.8.24`
-   Updated `componentFirst` blade directive for laravel version `5.8.22`
-   Updated `error` blade directive for laravel version `5.8.13`
-   Updated `canany` blade directive for laravel version `5.6.23`
-   Updated `dump` blade directive for laravel version `5.6.8`
-   Updated `csrf` && `method` blade directive for laravel version `5.6.0`
-   Updated `includeFirst` blade directive for laravel version `5.5.5`
-   Updated `json` blade directive for laravel version `5.5.3`
-   Updated `switch` blade directive for laravel version `5.5.0`
-   Updated `auth` && `guest` blade directive for laravel version `5.4.29`
-   Updated `isset` blade directive for laravel version `5.4.16`

## [1.20.5 - 2023-03-12]

### `Fixed`

-   [Bug#29](https://github.com/porifa/vscode-laraphense/issues/29): Showing wrong path of view on hover

## [1.20.4 - 2023-01-10]

### `Changed`

-   Update README

## [1.20.3 - 2023-01-01]

### `Fixed`

-   [Bug#26](https://github.com/porifa/vscode-laraphense/issues/26): Validation Rules are not showing in Form Request

### `Changed`

-   Go to view uses different key, use <`disableGoToView`> instead of <`goToView`>

## 1.20.2

### `Fixed`

-   [Bug#20](https://github.com/porifa/vscode-laraphense/issues/20): Auto completion for nest method doesn't work
-   [Bug#22](https://github.com/porifa/vscode-laraphense/issues/22): Go to component invalid path on windows
-   [Bug#23](https://github.com/porifa/vscode-laraphense/issues/23): Go to View/Component doesn't work with self closing tag without space

## 1.20.1

### `Added`

-   Added `decimal` validation rules for laravel version `9.45.0`
-   Added `ulid` and `ascii` validation rules for laravel version `9.44.0`

## 1.20.0

### `Whats Changed`

### Show Suggestions based on Laravel version

-   Blade Directive Based on Laravel Version
-   Blade Validation Rules on Laravel Version
-   Added `lowercase` and `uppercase` validation rules for laravel version `9.40.0`
-   Added `min_digits` and `max_digits` validation rules for laravel version `9.26.0`
-   Updated `vite` blade directive for laravel version `9.19.0`
-   Updated `disabled` blade directive for laravel version `9.0.2`

## 1.19.1

### `Whats Changed`

-   Improve proformace for go to view
-   Go to view uses different key, use <`goToView`> instead of <`quickJump`>
-   Removed folder Tip option since it is displayed only when required

## 1.19.0

### `Added`

-   Toggle Asset Auto Completion with key <`disableAssetCompletion`>
-   Toggle Auth Auto Completion with key <`disableAuthCompletion`>
-   Toggle Config Auto Completion with key <`disableConfigCompletion`>
-   Toggle Controller Auto Completion with key <`disableControllerCompletion`>
-   Toggle Eloquent Auto Completion with key <`disableEloquentCompletion`>
-   Toggle Env Auto Completion with key <`disableEnvCompletion`>
-   Toggle Middleware Auto Completion with key <`disableMiddlewareCompletion`>
-   Toggle Mix Auto Completion with key <`disableMixCompletion`>
-   Toggle Route Auto Completion with key <`disableRouteCompletion`>
-   Toggle Translation Auto Completion with key <`disableTranslationCompletion`>
-   Toggle Validation Auto Completion with key <`disableValidationCompletion`>
-   Toggle View Auto Completion with key <`disableViewCompletion`>

### `Fixed`

-   Toggle Blade Auto Completion with different key <`disableBladeCompletion`>

## 1.18.1

### `Fixed`

-   Completion item type for asset

## 1.18.0

### `Added`

-   Curly Braces Spacer

## 1.17.0

### `Added`

-   Support for `@livewire` directive for go to view

### `Fixed`

-   Use of multiple Directory Separator for view create
-   Use of multiple Directory Separator for go to view

## 1.16.1

### `Fixed`

-   Use of Hyphen (-) in command Pallet for view create

### `Added`

-   Support for `nest` method

## 1.15.1

### `Fixed`

-   Auto Suggest non existing view files only

## 1.15.0

### `Added`

-   Auto Suggest to create view file from view functions

## 1.14.0

### `Added`

-   env File Syntax Highlighting

## 1.13.0

### `Added`

-   Go to View

## 1.12.0

### `Added`

-   Laravel View Creation

## 1.11.0

### `Added`

-   Laravel Mix Completion

### 1.10.0

### `Added`

-   View Completion

### 1.9.0

### `Added`

-   Validation Completion

### 1.8.0

### `Added`

-   Translation Completion

### 1.7.0

### `Added`

-   Middleware Completion

### 1.6.0

### `Added`

-   Env Completion

### 1.5.0

### `Added`

-   Eloquent Completion

### 1.4.0

### `Added`

-   Config Completion

### 1.3.0

### `Added`

-   Auth Completion

### 1.2.0

### `Added`

-   Assets Completion

### 1.1.0

### `Added`

-   Route Completion

### 1.0.0

-   First Stable Release

### 0.0.2

### `Added`

-   @vite blade directive

### v0.0.1

### `Added`

-   Blade snippets
