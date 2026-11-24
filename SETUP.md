# Install your GitHub profile

Copy `README.md`, the entire `assets/` directory, and `.github/workflows/profile-cards.yml` into the root of your public **danielmarkjohn/danielmarkjohn** repository. Keep the directory structure intact. These files replace the profile README; they are not intended for the MCP connection manager project.

The package includes initial widget SVGs, so the README renders before automation runs. The banner and typing animation are also stored in the repository. The only images loaded from an external service while viewing the profile are the Shields.io badges.

Open **Actions → Update profile cards → Run workflow** after adding the files. The workflow is also configured to run when its file changes and daily at **08:47 IST (03:17 UTC)**. Scheduled runs can be delayed by GitHub. The workflow uses GitHub's automatically supplied `GITHUB_TOKEN`; no personal access token is required. It requests `contents: write` to commit the four updated SVG cards. Repository policies or branch protection may require you to allow those bot commits.

If a refresh fails, the previous committed images remain visible. Initial downloaded cards may reflect their upstream provider's cache; future successful runs replace them. Statistics cover the data the configured providers can access, not your complete professional output. The language card measures repository composition, not skill level.

The AI section is deliberately framed as current focus and exploration. RAG remains a learning/prototyping area. Add named frameworks and concrete AI/MCP project links when you want to showcase work you've actually done.

## What's included

- A custom SVG banner with a dark cyan/violet architecture motif.
- An animated focus line, with a reduced-motion fallback.
- AI-first profile copy: LLM integrations, MCP, agents, RAG, and AI quality.
- A compact core stack and expandable wider toolkit.
- Links to existing public repositories and your public LinkedIn profile.
- Statistics, language distribution, streak, and recent activity cards.
- A daily refresh workflow that stores cards in your repository.

## Sources and widget credits

- [GitHub profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [Stats Action inputs](https://github.com/stats-organization/github-readme-stats-action)
- [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [Activity Graph and current endpoint](https://github.com/Ashutosh00710/github-readme-activity-graph)
- [Shields.io](https://shields.io)

The original visitor counter and random quote are replaced by useful activity widgets and a consistent closing message. The original top-contributions card is replaced by direct project links.

## Preview and verification

Open `preview.html` in a browser for an approximate GitHub-style Markdown preview. It supports dark/light system appearance; GitHub remains the final layout reference. The live browser preview tool was unavailable in this session. The custom banner and chart SVGs were rendered and inspected locally, all 22 badge endpoints returned valid SVGs, and local image links and alt text were checked. The workflow received local syntax checks but has not been run in your GitHub account. `banner-preview.png`, `preview.html`, and this setup guide are optional local review files; only the README, assets, and workflow need to be uploaded.
