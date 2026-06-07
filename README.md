# Wedding Invitation Website

This is a static wedding invitation site that can be hosted directly with GitHub Pages.

## Customize The Invitation

Open `index.html` and edit the `SITE` block near the bottom of the file.

- Change names, date, venue, map text, note text, and RSVP settings in `SITE`.
- Change colors in `SITE.colors`.
- Change photos in `SITE.photos`.
- Add your own images inside `assets/photos/`, then use paths like `assets/photos/cover.jpg`.

## Guest Links

Your Google Sheet should keep these columns:

```text
Name | GuestID | AccessCode | Table | RSVPLink
```

Send guests links in this format:

```text
https://your-github-username.github.io/your-repo-name/?guest=john-doe&code=AB123
```

To preview the design without a guest code:

```text
index.html?preview=true
```

## GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, go to Settings > Pages.
3. Set the source to your main branch and root folder.
4. Use the generated Pages URL for your invitation links.

The invitation is client-side only. Anyone with the correct personal link can open it, so avoid placing highly sensitive information in the page or public Google Sheet.
