# AGENTS.md — organization profile

This repository is public and holds the organization profile that GitHub renders at
<https://github.com/eliminize>: [`profile/README.md`](profile/README.md). `profile/assets/` keeps
only the source of the organization avatar.

- **A signpost, not the pitch.** The player-facing site, <https://eliminize.github.io/> (checkout
  `eliminize.github.io`), carries the briefing and every picture. The profile is plain text: one line on
  what the game is and links to the game, the site and the feedback form. The org page is also where
  issues get triaged, so it must stay quiet: no screenshots, no banner, no big centered heading. Do not
  grow it back into a copy of the site.
- **Change it when the headline changes**, not whenever a number moves.
- **Write for players**, never developers: no issue references, plans, risks, playtests or roadmap.
- **No images in the profile.** If one ever comes back, reference it by absolute
  `raw.githubusercontent.com` URL: the GitHub mobile app does not resolve relative paths in the org profile.
- **`main` is the published branch.** Commit on it directly unless the user asks for a branch or a pull
  request; push only when the user asks.

The organization may later host a public issue board or discussions for player feedback; that is not
decided, so the profile links to neither.
