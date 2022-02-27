# NoRussian
### Volunteer DoS tool via HTML + JS

Made to be user friendly and simple to use - as to maximize the amount of people able to help.

Running the HTML locally on your device will run a DoS attack on Russian websites, through complete volunteering.

### Usage

Disabling CORS is necessary to be able to get the most performance out of this script.
See how [here](https://stackoverflow.com/a/58658101/1644554).

Chrome Windows:

1. Clone the repository or download the ZIP archive from the upper right button: Code->Download ZIP to your local machine
2. If you download the archive as zip, unzip it to any folder on your machine
3. Open terminal (windows key and type cmd, to find Command Prompt) and ENTER
4. You need to know what is the path to your chrome browser, by default it should be something like: `"C:\Program Files\Google\Chrome\Application\chrome.exe"`, if you don't know it, find Chrome icon on desktop, right click on it, select Properties and copy the path from target box
5. in Command Prompt copy paste: `"[CHROME PATH HERE]/chrome.exe" --disable-web-security` (replace [CHROME PATH HERE] with the actual path from above)

Chrome Mac:

`open -na Google\ Chrome --args --user-data-dir=/tmp/temporary-chrome-profile-dir --disable-web-security --disable-site-isolation-trial`

Other browsers:
Feel free to make a code commit.

### Disclaimer / Warning

All the contents of this repository should be used for authorized and/or educational purposes only. Any misuse of this repository will not be the responsibility of the author or of any other collaborator.

### Notable Projects

https://github.com/erkexzcx/stoppropaganda

Runs headless on Linux servers - as well as in Docker, which is extremely easy to setup, for those who are already familiar.
If you have any site recommendations for us, might be helpful to doubleback to them with an issue, or better yet, a pull request.

### Credits

Forked from https://github.com/ajax-lives/NoRussian

Forked from https://stop-russian-desinformation.near.page/
