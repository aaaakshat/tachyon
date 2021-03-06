# Tachyon
A multithread downloader created after facing the hardships of downloading with bandwidth throttling.

## Installation
To install tachyon you need to have python3. If you are on a MacOS based device, you can use homebrew in your terminal:
```shell
$ brew install python3
```
Then you can use pip to install the python file:
```shell
# Note: I used the name 'tachydownload' since the name 'tachyon' is taken.
$ pip install tachydownload
```

## Usage
To use tachyon, you should be able to run the following from the terminal:
```shell
$ tachyon [DOWNLOAD_URL]
```
Or if you would like to add a filename:
```shell
$ tachyon -n [SAVE_AS_NAME] [DOWNLOAD_URL]
```

## Errors
If you receive a module not found error, just run:
```shell
$ pip install requests click tqdm
```
If the issue persists, individually update the packages by running:
```shell
$ pip install [PACKAGE_NAME] --upgrade
```

## License
This software is licensed under the MIT License. It allows you to do nearly anything you want with it, however please do check the LICENSE text file for more details.

###### WRITTEN IN PYTHON
