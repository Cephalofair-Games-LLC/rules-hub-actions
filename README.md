# Actions

This repository houses the actions used to build the rules hub.

These are the currently available actions:

## [build-hub](build-hub)

This is the heart of the magic. This action contains python code that builds the final hub and uploads the results to github pages.

## [trigger-hub](trigger-hub)

This action is used by the language translations to tell the main hub that it needs to update the its pointer.

## [update-hub](update-hub)

This action is used in the main hub repository and responds to the [trigger-hub](trigger-hub) calls from translations.
