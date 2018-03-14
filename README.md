# another-npm

A major breaking change 1.0.0 - (increases the major and pushes a release/publish)

A feature change 1.1.0 with breaking change - (increases the minor and pushes a release/publish)

A doc change 1.1.0 - no change

A feature change 1.2.0 without breaking change - (increases the minor and pushes a release/publish)

A Fix 1.2.1 - (increases the patch and pushes a release/publish)

A Style commit - no change

A Refactor - no change

A Perf - 1.2.2 - (increases the patch and pushes a release/publish)

A test - no change

A build - no change

A ci - no change

A chore - no change

A revert - no change

So....
1.2.3 (Major.Minor.Patch)

- Any type of commit can force a release/publish by answering yes to "Are there any breaking changes?"

- Changes that trigger a release/publish (without having to answer yes to the breaking changes question)
    | Type | w/out breaking change | with breaking change |
    |:----:|:----:|:----:|
    |Feat|increases minor|increases major|
    |Fix|increases patch|increases ?|
    |Perf|increases patch|increases ?|

- Changes that do not trigger a release/publish (unless you answer yes to the breaking change question)
  - Doc
  - Style
  - Refactor
  - Test
  - Build
  - CI
  - Chore
  - Revert