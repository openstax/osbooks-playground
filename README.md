# OpenStax Book Playground

The repo is a playground to try out the OpenStax's POET editing plugin in Gitpod.

## How to edit

To edit this book in Gitpod, click [here](https://gitpod.io/#https://github.com/openstax/osbooks-playground) and Gitpod will automatically open and load the OpenStax editor plugin.

## Adding a New Collection

If you want to add a new collection (new book) to the POET playground, you need to update the following sections:
  - A new line in the `META-INF/books.xml`
  - A new `{slug}.collection.xml`, which can be copied from https://github.com/openstax/template-osbooks-new/
  - Add the slug to the `cannonical.json`

## Refreshing repo

If you push changes in POET, those changes will be made to this repo. The repo will be cleaned from time to time, in case someone breaks something.
