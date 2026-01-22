# Cool URIs on ariel-os.org

[Cool URIs don't change](https://www.w3.org/Provider/Style/URI),
and everything about Ariel OS is cool.
Therefore, our URIs don't change.

To ensure that our URIs don't change
even when the technology we serve them with changes
or the content of the URIs changes,
this document keeps track of which URIs we minted in the first place.

When we start placing actual content,
we don't need to track every single path,
but we should have a rough plan for how links stay working.

## Active URIs

* <https://ariel-os.org/>

  Running a website, following a URI style with trailing slashes and thus no technology specific file names.

  We care about most paths (initlally, `/`, `/imprint/`, `/blog/` and `/blog/*/`),
  and plan to issue redirects should we later decide on a different structure.

  We do not care about long-term stability of included resources:
  `/fonts/`, `/css/`, `/favicons{.*,/}`;
  in fact, some of those use deliberately ephemeral names to combat cache mismatches.

* <https://www.ariel-os.org/>

  Pure redirect to ariel-os.org for those whose fingers can't let go of that habit.

* <https://crab.ariel-os.org/>

* <https://ci.ariel-os.org/> is WIP as of 2025-05-21.

  All resources there relate to individual CI runs;
  those are so numerous and only ephemerally useful
  that no attempt is made for anything on there to be long-lived.
  (We might even place notes there that apart from the dashboard at `/`,
  none of this should be relied on for longer than a few days).

* All `http://` URIs just redirect to `https://`
