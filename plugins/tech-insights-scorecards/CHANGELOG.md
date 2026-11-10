# @openchoreo/backstage-plugin-tech-insights-scorecards

## 1.6.0-m.2

### Minor Changes

- 145586f: Publish the Scorecards plugins: the Scorecards frontend plugin, the
  dynamic-checks Tech Insights backend module, and the permissions they share.
  They now release in lockstep with the other `@openchoreo/*` packages.
- 9569e08: Add the Scorecards overview and entity views. The Scorecards page opens with
  the share of published checks passing, with a breakdown by kind and by check.
  Entities get a Scorecards tab with their tier, pass rate and check results, and
  Systems, Domains and Groups roll up the entities that belong to them. A summary
  card for the Overview tab and an `EntityScorecardRankChip` are also included.

### Patch Changes

- Updated dependencies [145586f]
  - @openchoreo/backstage-plugin-tech-insights-dynamic-checks-common@2.0.0-next.3
