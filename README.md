# FC Ukraine München

This is an official FC Ukraine München website.

## Build instructions for productions

```shell
rm -rf docs/ && hugo
```

## Build instructions for development

```shell
hugo server --disableFastRender
```

## Content Management System (CMS)

This project uses Netlify CMS for content management. You can access the CMS to edit posts and pages.

### Accessing the CMS

1.  Go to [https://fcukrainemuenchen.de/admin/](https://fcukrainemuenchen.de/admin/).
2.  Log in using your credentials. If you don't have an account, please contact an administrator.

### Managing Content

Once logged in, you will see the main dashboard with the available content types (Collections).

#### Collections

*   **Posts**: For creating and editing news articles and updates.
    *   Fields: Title, Publish Date, Image, Body.
    *   Supports Ukrainian and German versions.
*   **Pages**: For editing the main pages of the website.
    *   **Schedule**: To update the team's schedule.
    *   **Sponsors**: To manage the sponsors' page.
    *   **Contacts**: To edit the contact information.
    *   All page fields support Ukrainian and German.

### How to Edit

1.  Click on a collection on the left-hand side (e.g., "Posts").
2.  Click on an existing entry to edit it, or click "New Post" to create a new one.
3.  For multilingual content, you will see tabs for each language (`uk` and `de`).
4.  Make your changes in the editor.
5.  Click "Publish" to save your changes. The changes will be committed to the `main` branch and the website will be updated automatically.
