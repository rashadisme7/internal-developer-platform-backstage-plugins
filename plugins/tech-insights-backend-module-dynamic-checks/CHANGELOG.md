# @openchoreo/backstage-plugin-tech-insights-backend-module-dynamic-checks

## 1.6.0-m.2-eval

### Minor Changes

- 145586f: Publish the Scorecards plugins: the Scorecards frontend plugin, the
  dynamic-checks Tech Insights backend module, and the permissions they share.
  They now release in lockstep with the other `@openchoreo/*` packages.
- 4808a76: An entity's check results and facts now follow access to the entity. Running
  checks for one entity, and reading its latest facts or their history, answer
  403 when the caller can't read the entity in the catalog. The bulk check run
  lets holders of the dynamic-check read permission through; anyone else must be
  able to read every entity they list.

### Patch Changes

- Updated dependencies [145586f]
  - @openchoreo/backstage-plugin-tech-insights-dynamic-checks-common@2.0.0-next.3
