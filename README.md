# [ECMAScript](https://github.com/tc39/ecma262) proposals

* [Stage 1 Proposals](stage-1-proposals.md)
* [Stage 0 Proposals](stage-0-proposals.md)
* [Finished Proposals](finished-proposals.md)
* [Inactive Proposals](inactive-proposals.md)

[ECMAScript Internationalization API Specification](ecma402/README.md) proposals

## Contributing new proposals

Please see [Contributing to ECMAScript](https://github.com/tc39/ecma262/blob/HEAD/CONTRIBUTING.md) for the most up-to-date information on contributing proposals to this standard.

## Active proposals

Proposals follow [this process document](https://tc39.es/process-document/).
This list contains only stage 2 proposals and higher that have not yet been withdrawn/rejected, or become finished.
Stage 2 indicates that the committee expects these features to be developed and eventually included in the standard.

### Stage 3

| Proposal                                                                       | Author                                                                  | Champion                                                                | Tests                                            | <sub>Last Presented</sub>                                  | [Requires implementer coordination?](https://github.com/tc39/how-we-work/blob/requires-implementer-coordination/requires-implementer-coordination.md) |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------------- | --- |
| [Legacy RegExp features in JavaScript][regexp-legacy]                          | Claude Pache                                                            | Mark Miller<br />Claude Pache                                           | [:white_check_mark:][tests-regexp-legacy]        | <sub>[May&nbsp;2017][regexp-legacy-notes]</sub>            |
| [`Atomics.waitAsync`][nonblocking]                                             | Lars Hansen                                                             | Shu-yu Guo<br />Lars Hansen                                             | [:white_check_mark:][tests-nonblocking]          | <sub>[December&nbsp;2019][nonblocking-notes]</sub>         |
| [JSON Modules][json-modules]                                                   | Myles Borins<br />Sven Sauleau<br />Dan Clark<br />Daniel Ehrenberg     | Myles Borins<br />Sven Sauleau<br />Dan Clark<br />Daniel Ehrenberg     | [:white_check_mark:][json-modules-tests]         | <sub>[January&nbsp;2021][json-modules-notes]</sub>         |
| [Temporal][temporal]                                                           | Philipp Dunkel<br />Maggie Johnson-Pint<br />Matt Johnson-Pint<br />Brian Terlson<br />Shane Carr<br />Ujjwal Sharma<br />Philip Chimento<br />Jason Williams<br />Justin Grant | Philipp Dunkel<br />Maggie Johnson-Pint<br />Matt Johnson-Pint<br />Brian Terlson<br />Shane Carr<br />Ujjwal Sharma<br />Philip Chimento<br />Jason Williams<br />Justin Grant| [:white_check_mark:][temporal-tests] | <sub>[March&nbsp;2021][temporal-notes]</sub> | ⚠️ ([issues](https://github.com/tc39/proposal-temporal/milestone/11)) |
| [Resizable and growable ArrayBuffers][resizable]                               | Shu-yu Guo                                                              | Shu-yu Guo                                                              | [:white_check_mark:][resizable-tests]            | <sub>[May&nbsp;2021][resizable-notes]</sub>                |
| [ShadowRealm][shadowrealm]                                                     | Caridy Patiño<br />Jean-Francois Paradis              | Dave Herman<br />Mark Miller<br />Caridy Patiño<br />Leo Balter<br />Rick Waldron<br />Chengzhong Wu | [:white_check_mark:][realms-tests]    | <sub>[December&nbsp;2021][realms-notes]</sub>              |
| [Array Grouping][array-grouping]                                               | Justin Ridgewell                                      | Justin Ridgewell                                                                          | :white_check_mark: (`array-grouping` feature)    | <sub>[December&nbsp;2021][array-grouping-notes]</sub>      |
| [Decorators][decorators]                                                       | Daniel Ehrenberg<br />Chris Garrett                   | Chris Garrett                                                                             | [:white_check_mark:][decorators-tests] (initial tests) | <sub>[March&nbsp;2022][decorators-notes]</sub>       |
| [RegExp v flag with set notation + properties of strings][regexp-v-flag]       | Markus Scherer<br />Mathias Bynens                    | Mathias Bynens                                                                            | :white_check_mark: (`regexp-v-flag` feature)     | <sub>[March&nbsp;2022][regexp-v-flag-notes]</sub>          |
| [JSON.parse source text access][json-parse-source]                             | Richard Gibson                                        | Richard Gibson                                                                            | :question:                                       | <sub>[June&nbsp;2022][json-parse-source-notes]</sub>       |
| [RegExp Modifiers][regexp-modifiers]                                           | Ron Buckton                                           | Ron Buckton                                                                               | :question:                                       | <sub>[June&nbsp;2022][regexp-modifiers-notes]</sub>        |
| [Duplicate named capture groups][named-capture-groups]                         | Kevin Gibbons                                         | Kevin Gibbons                                                                             | [:white_check_mark:][named-capture-groups-tests] | <sub>[July&nbsp;2022][named-capture-groups-notes]</sub>    |
| [`Array.fromAsync`][from-async]                                                | J.S. Choi                                             | J.S. Choi                                                                                 | :question:                                       | <sub>[September&nbsp;2022][from-async-notes]</sub>         |
| [New Set methods][set-methods]                                                 | Michał Wadas<br />Sathya Gunasekaran<br />Kevin Gibbons | Kevin Gibbons                                                                            | :question:                                       | <sub>[November&nbsp;2022][set-methods-notes]</sub>        |
| [Well-Formed Unicode Strings][usv-string]                                      | Guy Bedford<br />Bradley Farias                       | Guy Bedford<br />Bradley Farias<br />Michael Ficarra                                      | [:white_check_mark:][usv-string-tests]           | <sub>[November&nbsp;2022][usv-string-notes]</sub>          |
| [Sync Iterator helpers][iterator-helpers]                                           | Gus Caplan                                            | Michael Ficarra<br />Jonathan Keslin<br />Kevin Gibbons                                   | [:construction:][iterator-helpers-tests]         | <sub>[November&nbsp;2022][iterator-helpers-notes]</sub>    |
| [Explicit Resource Management][resource-management]                            | Ron Buckton                                           | Ron Buckton                                                                               | :question:                                       | <sub>[November&nbsp;2022][resource-management-notes]</sub> |
| [ArrayBuffer transfer][arraybuffer-transfer]                                   | Shu-yu Guo<br />Jordan Harband<br />Yagiz Nizipli     | Shu-yu Guo<br />Jordan Harband<br />Yagiz Nizipli                                         | :question:                                       | <sub>January&nbsp;2023</sub>                               |

### Stage 2

| Proposal                                                                       | Author                                                | Champion                                                                          | <sub>Last Presented</sub>                                             |
| ------------------------------------------------------------------------------ | ----------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [`function.sent` metaproperty][function-sent]                                  | Allen Wirfs-Brock                                     | HE Shi-Jun                                                                        | <sub>[July&nbsp;2019][function-sent-notes]</sub>                      |
| [`throw` expressions][throw-expressions]                                       | Ron Buckton                                           | Ron Buckton                                                                       | <sub>[January&nbsp;2018][throw-expressions-notes]</sub>               |
| [Function implementation hiding][censorship]                                   | Domenic Denicola<br />Michael Ficarra                 | Michael Ficarra                                                                   | <sub>[June&nbsp;2020][censorship-notes]</sub>                         |
| [Sequence properties in Unicode property escapes][unicode-sequence-properties] | Mathias Bynens                                        | Mathias Bynens                                                                    | <sub>[October&nbsp;2019][unicode-sequence-properties-notes]</sub>     |
| [collection normalization][collection-rekey]                                   | Bradley Farias                                        | Bradley Farias                                                                    | <sub>[January&nbsp;2019][richer-keys-notes]</sub>                     |
| [Array.isTemplateObject][isTemplateObject]                                     | Mike Samuel, Krzysztof Kotowicz                       | Krzysztof Kotowicz                                                                | <sub>[December&nbsp;2019][isTemplateObject-notes]</sub>               |
| [Async Explicit Resource Management][async-resource-management]                | Ron Buckton                                           | Ron Buckton                                                                       | <sub>November&nbsp;2022</sub>                                         |
| [`Map.prototype.emplace`][map-emplace]                                         | Bradley Farias                                        | Erica Pramer                                                                      | <sub>[July&nbsp;2020][map-emplace-notes]</sub>                        |
| [Dynamic Import Host Adjustment][]                                             | Mike Samuel, Krzysztof Kotowicz                       | Krzysztof Kotowicz                                                                | <sub>[December&nbsp;2019][Dynamic Import Host Adjustment notes]</sub> |
| [WeakRefs `cleanupSome`][cleanup-some]                                         | Yulia Startsev<br />Daniel Ehrenberg                  | Yulia Startsev<br />Daniel Ehrenberg                                              | <sub>[July&nbsp;2020][cleanup-some-notes]</sub>                       |
| [Record & Tuple][record-tuple]                                                 | Robin Ricard<br />Richard Button                      | Robin Ricard<br />Richard Button                                                  | <sub>[December&nbsp;2021][record-tuple-notes]</sub>                   |
| [Module Expressions][module-expressions]                                       | Surma<br />Daniel Ehrenberg<br />Nicolò Ribaudo       | Surma<br />Nicolò Ribaudo                                                         | <sub>[November&nbsp;2022][module-expressions-notes]</sub>             |
| [Pipeline Operator][pipeline]                                                  | J. S. Choi<br />James DiGioia<br />Ron Buckton<br />Tab Atkins | J. S. Choi<br />Ron Buckton<br />Tab Atkins                              | <sub>[August&nbsp;2021][pipe-notes]</sub>                             |
| [Destructure Private Fields][destructure-private]                              | Justin Ridgewell                                      | Justin Ridgewell                                                                  | <sub>[December&nbsp;2021][destructure-private-notes]</sub>            |
| [RegExp Buffer Boundaries (`\A`, `\z`, `\Z`)][regexp-buffer-boundaries]        | Ron Buckton                                           | Ron Buckton                                                                       | <sub>[December&nbsp;2021][regexp-buffer-boundaries-notes]</sub>       |
| [Decorator Metadata][decorator-metadata]                                       | Chris Garrett                                         | Chris Garrett                                                                     | <sub>[March&nbsp;2022][decorator-metadata-notes]</sub>                |
| [String.dedent][string.dedent]                                                 | Misha Kaletsky<br />Hemanth HM<br />Justin Ridgewell  | Hemanth HM<br />Justin Ridgewell                                                  | <sub>[June&nbsp;2022][string.dedent-notes]</sub>                      |
| [Import Reflection][import-reflection]                                         | Luca Casonato                                         | Guy Bedford<br />Luca Casonato                                                    | <sub>[November&nbsp;2022][import-reflection-notes]</sub>              |
| [JSON.parseImmutable][json-parse-immutable]                                    | Robin Ricard<br />Richard Button<br />Nicolò Ribaudo<br />Ashley Claymore | Robin Ricard<br />Richard Button<br />Nicolò Ribaudo<br />Ashley Claymore | <sub>July&nbsp;2022</sub>                                 |
| [Module Declarations][module-declarations]                                     | Daniel Ehrenberg<br />Nicolò Ribaudo                  | Daniel Ehrenberg<br />Mark Miller<br />Nicolò Ribaudo                             | <sub>[November&nbsp;2022][module-declarations-notes]</sub>            |
| [Symbol Predicates][symbol-predicates]                                         | Robin Ricard<br />Jordan Harband                      | Ashley Claymore<br />Jordan Harband                                               | <sub>January&nbsp;2023</sub>                                          |
| [Import Assertions][import-assertions]                                         | Myles Borins<br />Sven Sauleau<br />Dan Clark<br />Daniel Ehrenberg     | Sven Sauleau<br />Dan Clark<br />Daniel Ehrenberg<br />Nicolò Ribaudo | <sub>January&nbsp;2023</sub>                                    |
| [Async Iterator helpers][async-iterator-helpers]                               | Gus Caplan                                            | Michael Ficarra<br />Jonathan Keslin<br />Kevin Gibbons                           | <sub>January&nbsp;2023</sub>                                          |

:white_check_mark: means a pull request for tests was merged.

:question: means there is no pull request for tests yet.

:construction: means a pull request for tests was created, but not merged yet.

### Onboarding existing proposals

Proposals that are Stage 1 and above must be transferred to [the TC39 GitHub organization](https://github.com/tc39) for discoverability and archival purposes. To onboard a proposal that lives outside the TC39 organization:

1. Transfer your repository to the [@tc39-transfer](http://github.com/tc39-transfer) organization
  - if you are a TC39 delegate, but not a member of that organization, please contact [@LJHarb](https://github.com/ljharb)
2. One of the chairs ([@bterlson](https://github.com/bterlson), [@gesa](https://github.com/gesa), [@MylesBorins](https://github.com/MylesBorins), or [@robpalme](https://github.com/robpalme)) will transfer your repository to the TC39 organization the next chance they get.

Note that as part of the onboarding process your repository name may be normalized. Don't worry, repo redirects will continue to work **as long as** you never create a fork, or a new repository, with the same name - although Github Pages redirects will be broken (please update your links!).

[regexp-legacy]: https://github.com/tc39/proposal-regexp-legacy-features
[regexp-legacy-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2017-05/may-25.md#15ia-regexp-legacy-features-for-stage-3
[tests-regexp-legacy]: https://github.com/tc39/test262/pull/2650
[function-sent]: https://github.com/tc39/proposal-function.sent
[function-sent-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-07/july-23.md#making-functionsent-inactive
[decorators]: https://github.com/tc39/proposal-decorators
[decorators-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-03/mar-28.md#decorators-for-stage-3
[decorators-tests]: https://github.com/tc39/test262/pull/3512
[shadowrealm]: https://github.com/tc39/proposal-shadowrealm
[realms-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-14.md#shadowrealms-updates-and-potential-normative-changes
[realms-tests]: https://github.com/tc39/test262/pull/3046
[temporal]: https://github.com/tc39/proposal-temporal
[temporal-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-14.md#temporal-update
[temporal-tests]: https://github.com/tc39/test262/pulls?q=is%3Apr+is%3Amerged+temporal+in%3Atitle+
[nonblocking]: https://github.com/tc39/proposal-atomics-wait-async
[nonblocking-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-12/december-4.md#atomicswaitasync-for-stage-3
[tests-nonblocking]: https://github.com/tc39/test262/issues/2511
[throw-expressions]: https://github.com/tc39/proposal-throw-expressions
[throw-expressions-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2018-01/jan-24.md#13iiii-throw-expressions-for-stage-3
[censorship]: https://github.com/tc39/proposal-function-implementation-hiding
[censorship-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2020-06/june-2.md#function-implementation-hiding-for-stage-3
[richer-keys]: https://github.com/tc39/proposal-richer-keys
[richer-keys-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-01/jan-30.md#richer-keys-for-stage-2
[unicode-sequence-properties]: https://github.com/tc39/proposal-regexp-unicode-sequence-properties
[unicode-sequence-properties-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-10/october-2.md#update-on-sequence-property-escapes-in-unicode-regular-expressions
[resource-management]: https://github.com/tc39/proposal-explicit-resource-management
[resource-management-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#explicit-resource-management-for-stage-3
[async-resource-management]: https://github.com/tc39/proposal-async-explicit-resource-management
[standard-library]: https://github.com/tc39/proposal-javascript-standard-library
[standard-library-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2018-07/july-26.md#javascript-standard-library
[collection-rekey]: https://github.com/tc39/proposal-collection-normalization
[iterator-helpers]: https://github.com/tc39/proposal-iterator-helpers
[iterator-helpers-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#iterator-helpers-for-stage-3
[iterator-helpers-tests]: https://github.com/tc39/test262/pull/2818
[iterator-helpers]: https://github.com/tc39/proposal-async-iterator-helpers
[private-declarations]: https://github.com/tc39/proposal-private-declarations
[isTemplateObject]: https://github.com/tc39/proposal-array-is-template-object
[isTemplateObject-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-12/december-4.md#arrayistemplateobject-update
[map-emplace]: https://github.com/tc39/proposal-upsert
[map-emplace-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2020-07/july-22.md#upsert-now-renamed-emplace-updates--for-stage-3
[Dynamic Import Host Adjustment]: https://github.com/tc39/proposal-dynamic-import-host-adjustment
[Dynamic Import Host Adjustment notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2019-12/december-5.md#dynamic-import-host-adjustment-for-stage-2
[cleanup-some]: https://github.com/tc39/proposal-cleanup-some
[cleanup-some-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2020-07/july-21.md#weakrefs-for-stage-4--cleanupsome-for-stage-23
[json-modules]: https://github.com/tc39/proposal-json-modules
[json-modules-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-01/jan-25.md#json-modules-for-stage-3
[json-modules-tests]: https://github.com/tc39/test262/pull/2999
[record-tuple]: https://github.com/tc39/proposal-record-tuple
[record-tuple-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-15.md#records-and-tuples
[json-parse-source]: https://github.com/tc39/proposal-json-parse-with-source
[json-parse-source-notes]: https://github.com/tc39/notes/blob/main/meetings/2022-06/jun-07.md#jsonparse-source-text-access
[import-assertions]: https://github.com/tc39/proposal-import-assertions
[import-assertions-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2020-11/nov-17.md#import-assertions-status-update
[import-assertions-tests]: https://github.com/tc39/test262/pull/2980
[resizable]: https://github.com/tc39/proposal-resizablearraybuffer
[resizable-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-05/may-25.md#resizable-arraybuffers-for-stage-3
[resizable-tests]: https://github.com/tc39/test262/pulls?q=is%3Apr+is%3Amerged+resizable+in%3Atitle+
[module-expressions]: https://github.com/tc39/proposal-module-expressions
[module-expressions-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#module-expressions
[regexp-v-flag]: https://github.com/tc39/proposal-regexp-v-flag
[regexp-v-flag-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-03/mar-29.md#regexp-set-notation--unicode-properties-of-strings-for-stage-3
[pipeline]: https://github.com/tc39/proposal-pipeline-operator
[pipe-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-08/aug-31.md#pipeline-operator-for-stage-2
[destructure-private]: https://github.com/tc39/proposal-destructuring-private
[destructure-private-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-14.md#destructuring-private-fields
[array-grouping]: https://github.com/tc39/proposal-array-grouping
[array-grouping-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-14.md#array-grouping-for-stage-3
[from-async]: https://github.com/tc39/proposal-array-from-async
[from-async-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-09/sep-14.md#arrayfromasync-for-stage-3
[regexp-modifiers]: https://github.com/tc39/proposal-regexp-modifiers
[regexp-modifiers-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-06/jun-07.md#regexp-modifiers
[regexp-buffer-boundaries]: https://github.com/tc39/proposal-regexp-buffer-boundaries
[regexp-buffer-boundaries-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2021-12/dec-15.md#regexp-buffer-boundaries-for-stage-2
[decorator-metadata]: https://github.com/tc39/proposal-decorator-metadata
[decorator-metadata-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-03/mar-28.md#decorators-for-stage-3
[named-capture-groups]: https://github.com/tc39/proposal-duplicate-named-capturing-groups
[named-capture-groups-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-07/jul-20.md#duplicate-named-capturing-groups-for-stage-3
[named-capture-groups-tests]: https://github.com/tc39/test262/pulls?q=is%3Apr+is%3Amerged+Duplicate%2Bnamed%2Bcapture%2Bgroups+in%3Atitle+sort%3Aupdated-desc+
[string.dedent]: https://github.com/tc39/proposal-string-dedent
[string.dedent-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-06/jun-07.md#stringdedent
[import-reflection]: https://github.com/tc39/proposal-import-reflection
[import-reflection-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/nov-30.md#import-reflection
[json-parse-immutable]: https://github.com/tc39/proposal-json-parseimmutable
[usv-string]: https://github.com/tc39/proposal-is-usv-string
[usv-string-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/nov-30.md#stringiswellformed-
[usv-string-tests]: https://github.com/tc39/test262/pull/3661
[set-methods]: https://github.com/tc39/proposal-set-methods
[set-methods-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/nov-30.md#set-methods
[arraybuffer-transfer]: https://github.com/tc39-transfer/proposal-arraybuffer-transfer
[arraybuffer-transfer-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/nov-29.md#resizable-buffers-bug-fixes-104-106-108-and-transfer-future-proofing
[module-declarations]: https://github.com/tc39/proposal-module-declarations
[module-declarations-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-11/dec-01.md#module-declarations
[symbol-predicates]: https://github.com/tc39/proposal-symbol-predicates
[symbol-predicates-notes]: https://github.com/tc39/notes/blob/HEAD/meetings/2022-07/jul-20.md#symbol-predicates
