# Setup Windows

## Chrome

* Download Chrome here:
  * [Chrome](https://www.google.com/chrome/)

## VS Code

* Download VS Code here:
  * [VS Code](https://code.visualstudio.com/)
* Download the ``Remote`` Extension

## WSL

* Powershell Command
  * ``Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux``
* Get Ubuntu from Microsoft Store
  * [Ubuntu](https://www.microsoft.com/en-us/p/ubuntu-1804-lts/9n9tngvndl3q?activetab=pivot:overviewtab)
* Set up your user account
* update/upgrade packages
  * ``sudo apt update``
  * ``sudo apt upgrade``
* Pin your Ubuntu file tree to start
  * at the top level of your Ubuntu type:
    * `explorer.exe .`
  * save the explorer window that pops up

## Git

* git config --global user.name "Your Name"
* git config --global user.email your@email.com

## NodeJS

* Open Ubuntu to the root and run these commands
  * ``sudo apt install build-essential``
  * ``curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash``
  * ``. ./.bashrc``
  * ``nvm install --lts``
* Type ``which node`` , you should get something similar to this:
  * ``/home/warren/.nvm/versions/node/v14.15.5/bin/node``
  * the ``.nvm`` is important as we want to manage our node versions

## Commands

* ls
  * See all files and folders in the directory(folder) you're currently in
* cd `<folder>`
  * Navigate to a directory(folder)
* mkdir `<folder_name>`
  * Make a directory(folder) in whatever directory(folder) you're in
* touch `<file_name>`
  * Create a file in whatever directory(folder) you're currently in
* pwd
  * Shows you path to the current directory(folder) you're in
* cd ../
  * Travel upwards
* cd ./
  * Don't travel

## Folder Structure

* `app_academy` (**folder**)
  * `Module-1-Resources` (**folder**)
  * `week_1` (**folder**)
    * `w1d1` (**folder**)
      * `lecture`(**folder**)
        * `README.md`
        * ...
      * `projects` (**folder**)
        * `file1.js` (**file**)
        * `file2.js` (**file**)
        * ...
      * `homework` (**folder**)
        * `file1.js` (**file**)
        * `file2.js` (**file**)

## Additional Notes

* Link to clone Mod1Resources:
  * ``https://github.com/appacademy/Module-1-Resources.git``
  * [Setup Seminar](https://github.com/appacademy/Module-1-Resources/blob/main/week1/additional_resources/setup_seminar.md)
* Note taking in MD
  * [Markdown Intro](https://commonmark.org/help/tutorial/index.html)
  * [Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
