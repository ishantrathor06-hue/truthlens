# TruthLens — Product Decisions

## DP1 — Feed order
**Choice: Risk + recency.**

The public feed prioritizes claims with stronger triage signals while also keeping recent claims near the top. This makes the feed useful for newsroom triage without simply rewarding sensational or highly engaged content.

## DP2 — Visibility
**Choice: Unverified claims remain publicly visible with a prominent “Unverified” status.**

Holding every claim back until review would hide what a citizen group is actually seeing and investigating. Clear status labels let readers distinguish a submitted claim from a reviewed conclusion.

## DP3 — Editing
**Choice: No silent edits; changes preserve the original submission and review history.**

A misinformation-triage system needs an audit trail so reviewers and readers can understand what was originally submitted. If the claim wording or metadata changes in a production version, the prior version should remain recoverable and associated review decisions should not be silently overwritten.
