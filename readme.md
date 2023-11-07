# Calendar Sync for Logseq

## Install npm and clasp

```
$ sudo apt-get install -y npm
$ sudo npm install -g @google/clasp
```

## Login

```
$ clasp login
```

This creates local HTTP server to receive the callback from Google
authentication so if your default browser is not Chrome, it may be best to
paste the URL the command prints out into Chrome.

## Copy settings

```
$ cp settings.js.sample settings.js
```

Edit the `settings.js` file and add details for your calendars.

## Create a Google Apps Script project

TBC

```
$ clasp create --type api --title "Logseq Calendar Merge"
```

## Push the project

TBC

```
$ clasp push
```

## Add a trigger

TBA

