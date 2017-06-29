# AzureBookmarkSync

## What it does

Simple browser extension POC which goal is to allow you to sync favorites and backup them, based on your personal cloud drives (OneDrive,Google Drive,DropBox).

# Based on Bookmark-it

## What it does

To display the button, the extension registers a [browserAction](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/browserAction) in the manifest.

A background script will listen for tab events and update the browserAction icon correspondingly. It also listens for `browserAction.onClicked` events to create or remove a bookmark when the user has clicked the icon.

## What it shows

* how to use the various `bookmarks` functions
  * create a bookmark
  * remove a bookmark
  * search bookmarks by url
* how to register a browserAction
* how to listen for tab changes



Simple browser extension POC which goal is to allow you to sync favorites and backup them, based on your personal cloud drives (OneDrive,Google Drive,DropBox).