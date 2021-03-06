<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/silverstripe.php -->
<!-- Then run bin/docgen -->

# silverstripe

[Source](/recipe/silverstripe.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`shared_assets`](#shared_assets)
  * [`shared_dirs`](#shared_dirs)
  * [`writable_dirs`](#writable_dirs)
  * [`silverstripe_cli_script`](#silverstripe_cli_script)
* Tasks
  * [`silverstripe:build`](#silverstripebuild) — Run /dev/build
  * [`silverstripe:buildflush`](#silverstripebuildflush) — Run /dev/build?flush=all
  * [`deploy`](#deploy) — Deploy your project

## Config
### shared_assets
[Source](https://github.com/deployphp/deployer/search?q=%22shared_assets%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)



### shared_dirs
[Source](https://github.com/deployphp/deployer/search?q=%22shared_dirs%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

Silverstripe shared dirs

### writable_dirs
[Source](https://github.com/deployphp/deployer/search?q=%22writable_dirs%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)

* Overrides [`writable_dirs`](/docs/recipe/deploy/writable.md#writable_dirs) from `recipe/deploy/writable.php`

Silverstripe writable dirs

### silverstripe_cli_script
[Source](https://github.com/deployphp/deployer/search?q=%22silverstripe_cli_script%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)

Silverstripe cli script


## Tasks
### silverstripe:build
[Source](https://github.com/deployphp/deployer/search?q=%22silverstripe%3Abuild%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)

Helper tasks

### silverstripe:buildflush
[Source](https://github.com/deployphp/deployer/search?q=%22silverstripe%3Abuildflush%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)



### deploy
[Source](https://github.com/deployphp/deployer/search?q=%22deploy%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Asilverstripe.php)

Main task

This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`silverstripe:buildflush`](/docs/recipe/silverstripe.md#silverstripebuildflush)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)


