# mscardone.github.io

The landing page for **projects.scottcardone.com**.

This is a GitHub *user site*, so its custom domain sets the base URL for every project site on
the account. With `CNAME` set to `projects.scottcardone.com`, a project repo called `foo`
is served at `https://projects.scottcardone.com/foo/` with no per-repo configuration.

DNS: a `CNAME` record for `projects` pointing at `mscardone.github.io` (GoDaddy).

To add a project to the list, copy an `<a class="card">` block in `index.html` and point it at
`/<repo-name>/`.
