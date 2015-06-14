# DRK Punch Bag

No brain frontend workflow.

## Installation

Check `nvm list` to see whether you have node JS installed. If not, have the script run locally.

```
nvm install v0.10.17
nvm alias default v0.10.17
```

Then change your current working directory to the project. Install the grunt plugin using `npm install -g grunt-cli`.

In the working directory, run `npm install`, notice that it might take a while to finish. Just be patient.

Run `grunt serve` to start the server, the website will be automatically opened in browser.

## Development

Adding your CSS stuffs in `app/scss` folder INSTEAD of `app/styles`. All your changes will be live reloaded in browser.
