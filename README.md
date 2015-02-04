# ngLoadingScreen
Angular Directive which puts a overlay loading screen if is-loading attribute is True and removes it when False.

Attributes
-
* isLoading (Takes $scope.variable, true or false)
* src (path to svg/img)
* width (Default is 150px)
* height (Default is 150px)
* timer (Milliseconds - Default is 500ms)

Usage
-
```
<loading-screen is-loading="loadingView" src="/icons/heart.svg"></loading-screen>
```
