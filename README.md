# Content - Article Read Time

Suggested repository:

- `https://github.com/joomtheme/content-article-read-time`

## Files

- `updates/updates.xml` → upload to the repository at this exact path
- Release asset filename expected by `updates.xml`:

## Release steps

1. Create the repo `content-article-read-time` under `joomtheme`.
2. Commit `updates/updates.xml` to the `main` branch.
3. Create a GitHub Release tagged `v1.6.3`.
4. Upload the plugin ZIP asset named exactly:
   - `plg_content_readtime_j6_1.6.3.zip`
5. Verify this URL works:
   - `https://raw.githubusercontent.com/joomtheme/content-article-read-time/main/updates/updates.xml`

The plugin manifest already points to that raw GitHub URL as its update server.
