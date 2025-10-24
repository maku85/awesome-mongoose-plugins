# Awesome Mongoose Plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of plugins for [Mongoose](https://mongoosejs.com/) 🐒.  
> A collection of extensions to make your life with MongoDB easier.

---

## 📑 Contents
- [General Utilities](#-general-utilities)
- [Developer Tools](#-developer-tools)
- [Validation & Security](#-validation--security)
- [Caching & Performance](#-caching--performance)
- [Pagination & Query](#-pagination--query)
- [Internationalization (i18n)](#-internationalization-i18n)
- [Tree & Hierarchical Data](#-tree--hierarchical-data)
- [Timestamps & Audit](#-timestamps--audit)
- [File & Media Handling](#-file--media-handling)
- [Miscellaneous](#-miscellaneous)

---

## 🛠 General Utilities
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-deep-populate](https://github.com/buunguyen/mongoose-deep-populate) | ![stars](https://img.shields.io/github/stars/buunguyen/mongoose-deep-populate?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-deep-populate?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/buunguyen/mongoose-deep-populate?style=flat&label=%20) | Enable deep population of nested models. |
| [mongoose-troop](https://github.com/tblobaum/mongoose-troop) | ![stars](https://img.shields.io/github/stars/tblobaum/mongoose-troop?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-troop?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/tblobaum/mongoose-troop?style=flat&label=%20) | Adds modular, reusable plugins and methods to Mongoose schemas, promoting clean code and schema composition. |
| [mongoose-autopopulate](https://github.com/mongodb-js/mongoose-autopopulate) | ![stars](https://img.shields.io/github/stars/mongodb-js/mongoose-autopopulate?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-autopopulate?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mongodb-js/mongoose-autopopulate?style=flat&label=%20) | Automatically populates `ref` fields without calling `.populate()`. |
| [mongoose-findorcreate](https://github.com/drudge/mongoose-findorcreate) | ![stars](https://img.shields.io/github/stars/drudge/mongoose-findorcreate?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-findorcreate?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/drudge/mongoose-findorcreate?style=flat&label=%20) | Adds a `findOrCreate` helper method to Mongoose models, simplifying the pattern of finding a document or creating it if it does not exist. |
| [mongoose-relationship](https://github.com/sabymike/mongoose-relationship) | ![stars](https://img.shields.io/github/stars/sabymike/mongoose-relationship?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-relationship?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/sabymike/mongoose-relationship?style=flat&label=%20) | Manages bi-directional document references, keeping parent and child relationships automatically in sync. |
| [mongoose-long](https://github.com/mongoosejs/mongoose-long) | ![stars](https://img.shields.io/github/stars/mongoosejs/mongoose-long?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-long?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mongoosejs/mongoose-long?style=flat&label=%20) | Adds support for 64-bit integers (`Long`) in Mongoose schemas, enabling storage of large numeric values. |
| [mongoose-update-if-current](https://github.com/eoin-obrien/mongoose-update-if-current) | ![stars](https://img.shields.io/github/stars/eoin-obrien/mongoose-update-if-current?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-update-if-current?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/eoin-obrien/mongoose-update-if-current?style=flat&label=%20) | Brings optimistic concurrency control to documents by incrementing version numbers on each save and preventing previous versions of a document from being saved over the current version. |
| [mongoose-plugin-autoinc](https://github.com/nodkz/mongoose-plugin-autoinc) | ![stars](https://img.shields.io/github/stars/nodkz/mongoose-plugin-autoinc?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-plugin-autoinc?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/nodkz/mongoose-plugin-autoinc?style=flat&label=%20) | Auto-increments any ID field on schema every time a document is saved. |
| [mongoose-lean-virtuals](https://github.com/vkarpov15/mongoose-lean-virtuals) | ![stars](https://img.shields.io/github/stars/vkarpov15/mongoose-lean-virtuals?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-lean-virtuals?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vkarpov15/mongoose-lean-virtuals?style=flat&label=%20) | Adds support for virtuals in `.lean()` queries. |
| [mongoose-url-slugs](https://github.com/talha-asad/mongoose-url-slugs) | ![stars](https://img.shields.io/github/stars/talha-asad/mongoose-url-slugs?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-url-slugs?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/talha-asad/mongoose-url-slugs?style=flat&label=%20) | Automatically generates URL-friendly slugs for Mongoose documents based on one or more fields. |
| [mongoose-lean-defaults](https://github.com/douglasgabr/mongoose-lean-defaults) | ![stars](https://img.shields.io/github/stars/douglasgabr/mongoose-lean-defaults?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-lean-defaults?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/douglasgabr/mongoose-lean-defaults?style=flat&label=%20) | Adds schema default values to documents returned from `.lean()` queries. |
| [mongoose-lean-getters](https://github.com/vkarpov15/mongoose-lean-getters) | ![stars](https://img.shields.io/github/stars/vkarpov15/mongoose-lean-getters?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-lean-getters?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vkarpov15/mongoose-lean-getters?style=flat&label=%20) | Applies getters to `.lean()` query results. |
| [mongoose-legacy-pluralize](https://github.com/vkarpov15/mongoose-legacy-pluralize) | ![stars](https://img.shields.io/github/stars/vkarpov15/mongoose-legacy-pluralize?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-legacy-pluralize?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vkarpov15/mongoose-legacy-pluralize?style=flat&label=%20) | Restores Mongoose’s legacy pluralization logic for collection names, useful for backward compatibility with older codebases. |
| [mongoose-currency-convert](https://github.com/maku85/mongoose-currency-convert) | ![stars](https://img.shields.io/github/stars/maku85/mongoose-currency-convert?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-currency-convert?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/maku85/mongoose-currency-convert?style=flat&label=%20) | Adds automatic currency conversion capabilities to Mongoose models using real-time exchange rates. |


---

## 🧰 Developer Tools
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [swagger-mongoose](https://github.com/simonguest/swagger-mongoose) | ![stars](https://img.shields.io/github/stars/simonguest/swagger-mongoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/swagger-mongoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/simonguest/swagger-mongoose?style=flat&label=%20) | Generates Mongoose models and schemas from Swagger/OpenAPI definitions. |

---

## ✅ Validation & Security
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose) | ![stars](https://img.shields.io/github/stars/saintedlama/passport-local-mongoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/passport-local-mongoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/saintedlama/passport-local-mongoose?style=flat&label=%20) | Simplifies integration of Passport.js local authentication with Mongoose models, including password hashing and user management. |
| [mongoose-auth](https://github.com/bnoguchi/mongoose-auth) | ![stars](https://img.shields.io/github/stars/bnoguchi/mongoose-auth?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-auth?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/bnoguchi/mongoose-auth?style=flat&label=%20) | Provides authentication helpers for Mongoose models, supporting password hashing, OAuth, and user management. |
| [mongoose-unique-validator](https://github.com/blakehaswell/mongoose-unique-validator) | ![stars](https://img.shields.io/github/stars/blakehaswell/mongoose-unique-validator?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-unique-validator?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/blakehaswell/mongoose-unique-validator?style=flat&label=%20) | Validates uniqueness of fields before saving. |
| [mongoose-validator](https://github.com/leepowellcouk/mongoose-validator) | ![stars](https://img.shields.io/github/stars/leepowellcouk/mongoose-validator?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-validator?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/leepowellcouk/mongoose-validator?style=flat&label=%20) | Wrapper for `validator.js` to use as Mongoose validators. |
| [mongoose-beautiful-unique-validation](https://github.com/matteodelabre/mongoose-beautiful-unique-validation) | ![stars](https://img.shields.io/github/stars/matteodelabre/mongoose-beautiful-unique-validation?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-beautiful-unique-validation?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/matteodelabre/mongoose-beautiful-unique-validation?style=flat&label=%20) | Enhances MongoDB unique constraint errors with cleaner, user-friendly validation messages. |
| [mongoose-hidden](https://github.com/mblarsen/mongoose-hidden) | ![stars](https://img.shields.io/github/stars/mblarsen/mongoose-hidden?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-hidden?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mblarsen/mongoose-hidden?style=flat&label=%20) | Hides sensitive fields (like passwords or tokens) from `JSON.stringify()`. |
| [mongoose-acl](https://github.com/scttnlsn/mongoose-acl) | ![stars](https://img.shields.io/github/stars/scttnlsn/mongoose-acl?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-acl?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/scttnlsn/mongoose-acl?style=flat&label=%20) | Adds access control lists (ACL) to Mongoose models, enabling fine-grained permissions. |

---

## ⚡ Caching & Performance
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [cachegoose](https://github.com/boblauer/cachegoose) | ![stars](https://img.shields.io/github/stars/boblauer/cachegoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/cachegoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/boblauer/cachegoose?style=flat&label=%20) | Adds caching to Mongoose queries using Redis or other backends, reducing database load. |
| [ts-cache-mongoose](https://github.com/ilovepixelart/ts-cache-mongoose) | ![stars](https://img.shields.io/github/stars/ilovepixelart/ts-cache-mongoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/ts-cache-mongoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/ilovepixelart/ts-cache-mongoose?style=flat&label=%20) | Cache query and aggregate in mongoose using in-memory or redis. |

---

## 📊 Pagination & Query
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoosastic](https://github.com/mongoosastic/mongoosastic) | ![stars](https://img.shields.io/github/stars/mongoosastic/mongoosastic?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoosastic?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mongoosastic/mongoosastic?style=flat&label=%20) | Integrates Mongoose models with Elasticsearch, providing real-time indexing and search capabilities. |
| [mongoose-paginate-v2](https://github.com/aravindnc/mongoose-paginate-v2) | ![stars](https://img.shields.io/github/stars/aravindnc/mongoose-paginate-v2?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-paginate-v2?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/aravindnc/mongoose-paginate-v2?style=flat&label=%20) | Advanced pagination plugin for queries. |
| [mongoose-aggregate-paginate-v2](https://github.com/webgangster/mongoose-aggregate-paginate-v2) | ![stars](https://img.shields.io/github/stars/webgangster/mongoose-aggregate-paginate-v2?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-aggregate-paginate-v2?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/webgangster/mongoose-aggregate-paginate-v2?style=flat&label=%20) | Pagination for aggregation queries. |
| [mongoose-fuzzy-searching](https://github.com/VassilisPallas/mongoose-fuzzy-searching) | ![stars](https://img.shields.io/github/stars/VassilisPallas/mongoose-fuzzy-searching?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-fuzzy-searching?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/VassilisPallas/mongoose-fuzzy-searching?style=flat&label=%20) | Fuzzy full-text search across multiple fields. |
| [mongoose-paginate-ts](https://github.com/IGLU-Agency/mongoose-paginate-ts) | ![stars](https://img.shields.io/github/stars/IGLU-Agency/mongoose-paginate-ts?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-paginate-ts?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/IGLU-Agency/mongoose-paginate-ts?style=flat&label=%20) | TypeScript-friendly pagination plugin for Mongoose models, offering flexible query and result pagination utilities. |


---

## 🌍 Internationalization (i18n)
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-intl](https://github.com/alexsk/mongoose-intl) | ![stars](https://img.shields.io/github/stars/alexsk/mongoose-intl?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-intl?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/alexsk/mongoose-intl?style=flat&label=%20) | Adds multilingual field support to Mongoose schemas with locale fallback and helpers. |

---

## 🌳 Tree & Hierarchical Data
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-nested-set](https://github.com/groupdock/mongoose-nested-set) | ![stars](https://img.shields.io/github/stars/groupdock/mongoose-nested-set?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-nested-set?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/groupdock/mongoose-nested-set?style=flat&label=%20) | Implements the Nested Set pattern for hierarchical data. |
| [mongoose-tree](https://github.com/briankircho/mongoose-tree) | ![stars](https://img.shields.io/github/stars/briankircho/mongoose-tree?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-tree?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/briankircho/mongoose-tree?style=flat&label=%20) | Adds tree structure support to Mongoose schemas, enabling parent-child relationships and hierarchical queries. |
| [mongoose-mpath](https://github.com/vikpe/mongoose-mpath) | ![stars](https://img.shields.io/github/stars/vikpe/mongoose-mpath?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-mpath?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vikpe/mongoose-mpath?style=flat&label=%20) | Implements materialized path pattern for hierarchical data in Mongoose, enabling easy retrieval of ancestors, descendants, and subtrees. |
| [mongoose-materialized](https://github.com/janez89/mongoose-materialized) | ![stars](https://img.shields.io/github/stars/janez89/mongoose-materialized?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-materialized?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/janez89/mongoose-materialized?style=flat&label=%20) | Adds support for hierarchical data using the materialized path pattern. |
---

## ⏱ Timestamps & Audit
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-timestamp](https://github.com/drudge/mongoose-timestamp) | ![stars](https://img.shields.io/github/stars/drudge/mongoose-timestamp?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-timestamp?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/drudge/mongoose-timestamp?style=flat&label=%20) | Automatically adds `createdAt` and `updatedAt`. |
| [mongoose-version](https://github.com/saintedlama/mongoose-version) | ![stars](https://img.shields.io/github/stars/saintedlama/mongoose-version?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-version?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/saintedlama/mongoose-version?style=flat&label=%20) | Automatically maintains document version history. |
| [mongoose-patch-history](https://github.com/codepunkt/mongoose-patch-history) | ![stars](https://img.shields.io/github/stars/codepunkt/mongoose-patch-history?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-patch-history?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/codepunkt/mongoose-patch-history?style=flat&label=%20) | Maintains a history of changes to documents using JSON Patch format, allowing auditing and rollback of updates. |
| [mongoose-diff-history](https://github.com/mimani/mongoose-diff-history) | ![stars](https://img.shields.io/github/stars/mimani/mongoose-diff-history?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-diff-history?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mimani/mongoose-diff-history?style=flat&label=%20) | Tracks document diffs between versions for lightweight auditing. |
| [mongoose-history-plugin](https://github.com/Masquerade-Circus/mongoose-history-plugin) | ![stars](https://img.shields.io/github/stars/Masquerade-Circus/mongoose-history-plugin?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-history-plugin?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/Masquerade-Circus/mongoose-history-plugin?style=flat&label=%20) | Tracks changes to Mongoose documents over time, maintaining a history of modifications for auditing and rollback purposes. |
| [ts-patch-mongoose](https://github.com/ilovepixelart/ts-patch-mongoose) | ![stars](https://img.shields.io/github/stars/ilovepixelart/ts-patch-mongoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/ts-patch-mongoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/ilovepixelart/ts-patch-mongoose?style=flat&label=%20) | Track changes of mongoose models and save them as patch history (audit log) in separate collection. |
| [mongoose-history-trace](https://github.com/WelingtonMonteiro/mongoose-history-trace) | ![stars](https://img.shields.io/github/stars/WelingtonMonteiro/mongoose-history-trace?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-history-trace?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/WelingtonMonteiro/mongoose-history-trace?style=flat&label=%20) | Records detailed change logs of Mongoose documents, including who made the change and when, for audit and tracking purposes. |
| [mongoose-history-diff](https://github.com/borodayev/mongoose-history-diff) | ![stars](https://img.shields.io/github/stars/borodayev/mongoose-history-diff?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-history-diff?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/borodayev/mongoose-history-diff?style=flat&label=%20) | Tracks changes to Mongoose documents by storing diffs between versions, enabling efficient versioning and audit trails. |
| [mongoose-activity](https://github.com/kommix/mongoose-activity) | ![stars](https://img.shields.io/github/stars/kommix/mongoose-activity?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/@kommix//mongoose-activity?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/kommix/mongoose-activity?style=flat&label=%20) | Tracks and logs user activities or document changes, providing an easy way to audit events in Mongoose models. |


---

## 📎 File & Media Handling
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-attachments](https://github.com/heapsource/mongoose-attachments) | ![stars](https://img.shields.io/github/stars/heapsource/mongoose-attachments?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-attachments?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/heapsource/mongoose-attachments?style=flat&label=%20) | Adds file attachment support for Mongoose models with multiple storage backends. |

---

## 🎁 Miscellaneous
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-delete](https://github.com/dsanel/mongoose-delete) | ![stars](https://img.shields.io/github/stars/dsanel/mongoose-delete?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-delete?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/dsanel/mongoose-delete?style=flat&label=%20) | Soft delete with restore and query helpers. |
| [mongoose-sequence](https://github.com/ramiel/mongoose-sequence) | ![stars](https://img.shields.io/github/stars/ramiel/mongoose-sequence?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-sequence?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/ramiel/mongoose-sequence?style=flat&label=%20) | Auto-increment fields. |
| [mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) | ![stars](https://img.shields.io/github/stars/joegoldbeck/mongoose-encryption?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-encryption?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/joegoldbeck/mongoose-encryption?style=flat&label=%20) | Transparent field-level encryption. |
| [mongoose-field-encryption](https://github.com/wheresvic/mongoose-field-encryption) | ![stars](https://img.shields.io/github/stars/wheresvic/mongoose-field-encryption?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-field-encryption?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/wheresvic/mongoose-field-encryption?style=flat&label=%20) | Provides field-level encryption for Mongoose schemas, enabling transparent encryption and decryption of sensitive data. |
| [mongoose-crate](https://github.com/achingbrain/mongoose-crate) | ![stars](https://img.shields.io/github/stars/achingbrain/mongoose-crate?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-crate?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/achingbrain/mongoose-crate?style=flat&label=%20) | Handles file attachments in Mongoose models with support for multiple storage backends and file transformations. |

---

🔗 **Sources**: community plugins, npm, and [plugins.mongoosejs.io](https://plugins.mongoosejs.io).
