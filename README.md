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
| [mongoose-autopopulate](https://github.com/mongodb-js/mongoose-autopopulate) | ![stars](https://img.shields.io/github/stars/mongodb-js/mongoose-autopopulate?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-autopopulate?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mongodb-js/mongoose-autopopulate?style=flat&label=%20) | Automatically populates `ref` fields without calling `.populate()`. |
| [mongoose-relationship](https://github.com/sabymike/mongoose-relationship) | ![stars](https://img.shields.io/github/stars/sabymike/mongoose-relationship?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-relationship?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/sabymike/mongoose-relationship?style=flat&label=%20) | Manages bi-directional document references, keeping parent and child relationships automatically in sync. |
| [mongoose-lean-virtuals](https://github.com/vkarpov15/mongoose-lean-virtuals) | ![stars](https://img.shields.io/github/stars/vkarpov15/mongoose-lean-virtuals?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-lean-virtuals?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vkarpov15/mongoose-lean-virtuals?style=flat&label=%20) | Adds support for virtuals in `.lean()` queries. |
| [mongoose-lean-getters](https://github.com/vkarpov15/mongoose-lean-getters) | ![stars](https://img.shields.io/github/stars/vkarpov15/mongoose-lean-getters?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-lean-getters?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/vkarpov15/mongoose-lean-getters?style=flat&label=%20) | Applies getters to `.lean()` query results. |

---

## 🧰 Developer Tools
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [swagger-mongoose](https://github.com/simonguest/swagger-mongoose) | ![stars](https://img.shields.io/github/stars/simonguest/swagger-mongoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/swagger-mongoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/simonguest/swagger-mongoose?style=flat&label=%20) | Generates Mongoose models and schemas from Swagger/OpenAPI definitions. |

---

## ✅ Validation & Security
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-unique-validator](https://github.com/blakehaswell/mongoose-unique-validator) | ![stars](https://img.shields.io/github/stars/blakehaswell/mongoose-unique-validator?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-unique-validator?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/blakehaswell/mongoose-unique-validator?style=flat&label=%20) | Validates uniqueness of fields before saving. |
| [mongoose-validator](https://github.com/leepowellcouk/mongoose-validator) | ![stars](https://img.shields.io/github/stars/leepowellcouk/mongoose-validator?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-validator?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/leepowellcouk/mongoose-validator?style=flat&label=%20) | Wrapper for `validator.js` to use as Mongoose validators. |
| [mongoose-beautiful-unique-validation](https://github.com/matteodelabre/mongoose-beautiful-unique-validation) | ![stars](https://img.shields.io/github/stars/matteodelabre/mongoose-beautiful-unique-validation?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-beautiful-unique-validation?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/matteodelabre/mongoose-beautiful-unique-validation?style=flat&label=%20) | Enhances MongoDB unique constraint errors with cleaner, user-friendly validation messages. |
| [mongoose-hidden](https://github.com/mblarsen/mongoose-hidden) | ![stars](https://img.shields.io/github/stars/mblarsen/mongoose-hidden?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-hidden?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/mblarsen/mongoose-hidden?style=flat&label=%20) | Hides sensitive fields (like passwords or tokens) from `JSON.stringify()`. |
| [mongoose-acl](https://github.com/lykmapipo/mongoose-acl) | ![stars](https://img.shields.io/github/stars/scttnlsn/mongoose-acl?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-acl?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/scttnlsn/mongoose-acl?style=flat&label=%20) | Adds access control lists (ACL) to Mongoose models, enabling fine-grained permissions. |

---

## ⚡ Caching & Performance
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [cachegoose](https://github.com/boblauer/cachegoose) | ![stars](https://img.shields.io/github/stars/boblauer/cachegoose?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/cachegoose?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/boblauer/cachegoose?style=flat&label=%20) | Adds caching to Mongoose queries using Redis or other backends, reducing database load. |

---

## 📊 Pagination & Query
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-paginate-v2](https://github.com/aravindnc/mongoose-paginate-v2) | ![stars](https://img.shields.io/github/stars/aravindnc/mongoose-paginate-v2?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-paginate-v2?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/aravindnc/mongoose-paginate-v2?style=flat&label=%20) | Advanced pagination plugin for queries. |
| [mongoose-aggregate-paginate-v2](https://github.com/webgangster/mongoose-aggregate-paginate-v2) | ![stars](https://img.shields.io/github/stars/webgangster/mongoose-aggregate-paginate-v2?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-aggregate-paginate-v2?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/webgangster/mongoose-aggregate-paginate-v2?style=flat&label=%20) | Pagination for aggregation queries. |

---

## 🌍 Internationalization (i18n)
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-intl](https://github.com/ladjs/mongoose-intl) | ![stars](https://img.shields.io/github/stars/ladjs/mongoose-intl?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-intl?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/ladjs/mongoose-intl?style=flat&label=%20) | Adds multilingual field support to Mongoose schemas with locale fallback and helpers. |

---

## 🌳 Tree & Hierarchical Data
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-materialized](https://github.com/lykmapipo/mongoose-materialized) | ![stars](https://img.shields.io/github/stars/lykmapipo/mongoose-materialized?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-materialized?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/lykmapipo/mongoose-materialized?style=flat&label=%20) | Adds support for hierarchical data using the materialized path pattern. |
| [mongoose-nested-set](https://github.com/joegoldbeck/mongoose-nested-set) | ![stars](https://img.shields.io/github/stars/joegoldbeck/mongoose-nested-set?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-nested-set?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/joegoldbeck/mongoose-nested-set?style=flat&label=%20) | Implements the Nested Set pattern for hierarchical data. |

---

## ⏱ Timestamps & Audit
| Plugin | Stars | Downloads | Last commit | Description |
|--------|-------|-----------|-------------|-------------|
| [mongoose-timestamp](https://github.com/drudge/mongoose-timestamp) | ![stars](https://img.shields.io/github/stars/drudge/mongoose-timestamp?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-timestamp?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/drudge/mongoose-timestamp?style=flat&label=%20) | Automatically adds `createdAt` and `updatedAt`. |
| [mongoose-version](https://github.com/dsanel/mongoose-version) | ![stars](https://img.shields.io/github/stars/dsanel/mongoose-version?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-version?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/dsanel/mongoose-version?style=flat&label=%20) | Automatically maintains document version history. |
| [mongoose-diff-history](https://github.com/victorquinn/mongoose-diff-history) | ![stars](https://img.shields.io/github/stars/victorquinn/mongoose-diff-history?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-diff-history?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/victorquinn/mongoose-diff-history?style=flat&label=%20) | Tracks document diffs between versions for lightweight auditing. |

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
| [mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) | ![stars](https://img.shields.io/github/stars/joegoldbeck/mongoose-encryption?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-encryption?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/joegoldbeck/mongoose-encryption?style=flat&label=%20) | Transparent field-level encryption. |
| [mongoose-fuzzy-searching](https://github.com/VassilisPallas/mongoose-fuzzy-searching) | ![stars](https://img.shields.io/github/stars/VassilisPallas/mongoose-fuzzy-searching?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-fuzzy-searching?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/VassilisPallas/mongoose-fuzzy-searching?style=flat&label=%20) | Fuzzy full-text search across multiple fields. |
| [mongoose-sequence](https://github.com/ramiel/mongoose-sequence) | ![stars](https://img.shields.io/github/stars/ramiel/mongoose-sequence?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-sequence?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/ramiel/mongoose-sequence?style=flat&label=%20) | Auto-increment fields. |
| [mongoose-history](https://github.com/nassor/mongoose-history) | ![stars](https://img.shields.io/github/stars/nassor/mongoose-history?style=flat&label=%20) | ![downloads](https://img.shields.io/npm/dm/mongoose-history?style=flat&label=%20) | ![last-commit](https://img.shields.io/github/last-commit/nassor/mongoose-history?style=flat&label=%20) | Document versioning and history. |

---

🔗 **Sources**: community plugins, npm, and [plugins.mongoosejs.io](https://plugins.mongoosejs.io).
