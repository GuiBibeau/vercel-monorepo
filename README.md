## Vercel-Monorepo

### NB: With the recent launch and aquisition of turbo repo, this will soon get updated to a newer blog post

This is a example repo that shows a simple structure for a vercel monorepo. This is using yarn workspaces to add basic tooling a separation of concerns.

## How to deploy this to vercel.

each app inside the packages folder is to be treated as it's own vercel project. Using the CLI you can simply run `vercel` from those folders and follow the instructions in order to deploy them on vercel.
