## Version 1 (V1) Goals:

- Identify potentially affected code artifacts from a code change.
- Analyze code base to map dependencies (e.g., if Function A is modified, identify which function relies on it).
- Give simple output like which file/s changed and what else part in the code base might be affected.

## Version 1 (V1) Non-Goals:

- V1 will not analyze production traffic or run-time behaviors. It will only analyze static code base.
- V1 will only analyze and track code change impact in a single code-base (monorepo). Cross-repository impact tracking is deferred.
- V1 will not automatically trigger impact analysis whenever a new pull request is made.
- V1 will not generate risk score (e.g., Low, Medium, or High).
- V1 will only show what might be impacted by code change, but that doesn't stop you from merging your code.