# pulse-fast-deploy-fixture-manifest

Maps Fast Deploy fixture scenario tags to commit SHAs and expected identities
(see `docs/specs/fast_deploy.md` §22). Scenario commits do not self-reference
their own digests; this manifest is the authority for pinned expectations.

**Write policy:** only Maglev maintainers / agents with access to
`maglev-tech-test`. Never push to third-party upstream samples.
