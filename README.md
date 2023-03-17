# OpenStax Book Playground

The repo is a playground to try out the OpenStax's POET editing plugin in Gitpod.

## How to edit

It is recommended that you either fork this repo to your personal GitHub account or create a branch to edit on.

To edit this book in Gitpod, once viewing the correct branch or fork, place `https://gitpod.io/#` in front of your current url (e.g. `https://gitpod.io/#https://github.com/openstax/osbooks-playground` and Gitpod will automatically open and load the OpenStax editor plugin.

## Adding a New Collection

You can edit the Playgound collection in the repo, or you can create your own collection.

If you want to add a new collection (new book) to the POET playground, you need to update the following sections:
  - A new line in the `META-INF/books.xml`
  - A new `{slug}.collection.xml`, which can be copied from https://github.com/openstax/template-osbooks-new/
    - The relevant fields will need to be updated in collection.xml (slug, title, UUID, license, language).

## Refreshing repo

If you push changes in POET, those changes will be made to this repo. The repo will be cleaned from time to time, in case someone breaks something. If you are working on your own fork or branch, those changes won't be cleaned.
