# TruthLens — Civic Misinformation Triage

A polished, local-first MVP for an AI-based hackathon brief: a neutral civic-tech platform for triaging viral claims.

## Submission status

- Hackathon ID: `AZIS-QW7CZ7`
- Authentication: **Not implemented** (all features are accessible without an account)
- Standard API: **Not implemented in this MVP**. The project is a browser-based static app; no unsupported API contract is being claimed.
- Public GitHub repository: create after uploading this folder
- Public deployment: deploy `index.html` after uploading the repository

## Included
- Public claim feed
- Risk + recency ordering
- Claim submission workflow
- Platform and category metadata
- Risk flags
- Detailed claim view
- Reviewer workspace
- Review decisions: Verified / Disputed / Needs context
- Evidence and review notes
- Preserved submission/review history concept
- Light mode by default + dark mode toggle
- Responsive desktop/mobile layout
- No backend or API keys required for the demo

## Run
Open `index.html` in a modern desktop browser.

For a local server, from this folder run:

    python -m http.server 8000

Then open http://localhost:8000

## Demo credentials
No credentials are required for this local MVP.

## Hackathon ID
AZIS-QW7CZ7

**Important:** Replace the value above with the exact hackathon ID before submitting. The hackathon brief says the ID must appear in the root README.md.

## Product decisions
See `decisions.md`.

## Demo flow
1. Start on the public feed.
2. Show the risk + recency ordering and category filters.
3. Open a claim to show its evidence, risk signals and review history.
4. Submit a new claim and add two risk flags.
5. Open the Review queue.
6. Review the new claim and change its status.
7. Return to the public feed and show the updated status.
8. Toggle dark mode briefly, then return to light mode for the final frame.

## Design principle
TruthLens is neutral by design. It does not score ideologies or decide what people should believe. It records claims, surfaces review priorities, shows evidence/notes, and makes verification status explicit.


## Hackathon submission checklist

1. Confirm `README.md` contains the exact Hackathon ID `AZIS-QW7CZ7`.
2. Push the complete project to a **public GitHub repository**.
3. Deploy the app at a **public URL**.
4. Open the public URL in a fresh/private browser window and verify that no login is required.
5. Verify all five required features and all three decision-point behaviours.
6. Enter the GitHub URL and deployed app URL in the hackathon submission form.
7. State that the standard API is **not implemented** unless the selected track's API specification has been added.
8. Record a **3–4 minute** demo covering the five features in order plus DP1, DP2 and DP3.
