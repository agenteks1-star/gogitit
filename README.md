# GoGitIt

Open-source GitHub projects you can turn into paying work. Each one comes with a playbook: what it is, how you make money, who pays, what to charge, what the buyer gets, how to build it, how to find customers, and companies already doing it.

- Sort by fastest growing, top stars or most forks.
- Filter by genre (AI, Games, Websites & Apps, Online Stores, Business Software, Everyday Tools, Creative & Media, Tech & Data, Education), skill level and how you earn.
- Star an idea to save it for later. Stars are kept in your browser.
- Search the list, or jump to a live search of all of GitHub.
- Open-source licenses only, with a plain-English note on what each license allows.

## Daily scan with your own Claude key

Paste a Claude API key into the "Daily scan with your own Claude key" section. The first time you open the site after 6am each day (or when you tap Scan now), it updates stars and forks from GitHub and has Claude write playbooks for up to 5 new repos. You can also paste any GitHub repo link to get a playbook for it.

The key and the scan results stay in your browser. The key is sent only to Anthropic, and usage is billed to your Anthropic account.

## Files

- `index.html` is the site.
- `data.js` is the starting list of repos and playbooks.

## Use it

Turn on GitHub Pages (Settings, Pages, deploy from `main` / root), then open the address GitHub gives you.

The earlier version of GoGitIt (100 fresh repos a day, build-as filters, gist sync) is still in this repo's history.
