# mscardone.github.io

The landing page for **projects.scottcardone.com**.

This is a GitHub *user site*, so its custom domain sets the base URL for every project site on
the account. With `CNAME` set to `projects.scottcardone.com`, a project repo called `foo`
is served at `https://projects.scottcardone.com/foo/` with no per-repo configuration.

DNS: a `CNAME` record for `projects` pointing at `mscardone.github.io` (GoDaddy).

To add a project, copy an `<a class="card">` block (and its `.install` line) inside the right
`<details class="cat">` category in `index.html`, bump that category's count, and point the card at
`/<repo-name>/`.

Categories are `<details class="cat">` blocks; one with the `open` attribute starts expanded. To add a
category, copy a whole block and change the `<h2>` title.
