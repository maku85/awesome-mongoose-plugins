# Awesome Mongoose Plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of plugins for [Mongoose](https://mongoosejs.com/) 🐒.
> A collection of extensions to make your life with MongoDB easier.

---

## 📑 Contents
- [General Utilities](#general-utilities)
- [Developer Tools](#developer-tools)
- [Validation & Security](#validation--security)
- [Caching & Performance](#caching__performance)
- [Pagination & Query](#pagination--query)
- [Internationalization (i18n)](#internationalization_i18n)
- [Tree & Hierarchical Data](#tree--hierarchical-data)
- [Timestamps & Audit](#timestamps--audit)
- [File & Media Handling](#file__media_handling)
- [Miscellaneous](#miscellaneous)

---

## 🛠 General Utilities
- [mongoose-autopopulate](https://github.com/mongodb-js/mongoose-autopopulate) – Automatically populates `ref` fields without calling `.populate()`.
- [mongoose-relationship](https://github.com/jaumard/mongoose-relationship) – Manages bi-directional document references, keeping parent and child relationships automatically in sync.
- [mongoose-lean-virtuals](https://github.com/vkarpov15/mongoose-lean-virtuals) – Adds support for virtuals in `.lean()` queries.
- [mongoose-lean-getters](https://github.com/vkarpov15/mongoose-lean-getters) – Applies getters to `.lean()` query results.

---

## 🧰 Developer Tools
- [swagger-mongoose](https://github.com/adityamukho/swagger-mongoose) – Generates Mongoose models and schemas from Swagger/OpenAPI definitions, keeping your data layer and API documentation in sync.

---

## ✅ Validation & Security
- [mongoose-unique-validator](https://github.com/blakehaswell/mongoose-unique-validator) – Validates uniqueness of fields before saving.
- [mongoose-validator](https://github.com/leepowellcouk/mongoose-validator) – Wrapper for `validator.js` to use as Mongoose validators.
- [mongoose-beautiful-unique-validation](https://github.com/matteodelabre/mongoose-beautiful-unique-validation) – Enhances MongoDB unique constraint errors with cleaner, user-friendly validation messages.
- [mongoose-hidden](https://github.com/mblarsen/mongoose-hidden) – Hides sensitive fields (like passwords or tokens) from `JSON.stringify()`.
- [mongoose-acl](https://github.com/lykmapipo/mongoose-acl) – Adds access control lists (ACL) to Mongoose models, enabling fine-grained permissions and ownership-based access restrictions.

---

## ⚡ Caching & Performance
- [cachegoose](https://github.com/baugarten/cachegoose) – Adds caching to Mongoose queries using Redis or other backends, reducing database load and improving performance.

---

## 📊 Pagination & Query
- [mongoose-paginate-v2](https://github.com/aravindnc/mongoose-paginate-v2) – Advanced pagination plugin for queries.
- [mongoose-aggregate-paginate-v2](https://github.com/webgangster/mongoose-aggregate-paginate-v2) – Pagination for aggregation queries.

---

## 🌍 Internationalization (i18n)
- [mongoose-intl](https://github.com/ladjs/mongoose-intl) – Adds multilingual field support to Mongoose schemas with automatic locale fallback and helpers for setting or retrieving translations.

---

## 🌳 Tree & Hierarchical Data
- [mongoose-materialized](https://github.com/lykmapipo/mongoose-materialized) – Adds support for hierarchical data using the materialized path pattern. Perfect for nested categories, threaded comments, or organizational trees.
- [mongoose-nested-set](https://github.com/joegoldbeck/mongoose-nested-set) – Implements the Nested Set pattern for hierarchical data, allowing efficient queries for entire subtrees and ancestors.

---

## ⏱ Timestamps & Audit
- [mongoose-timestamp](https://github.com/drudge/mongoose-timestamp) – Automatically adds `createdAt` and `updatedAt`.
- [mongoose-version](https://github.com/dsanel/mongoose-version) – Automatically maintains document version history, allowing rollback and detailed audit of changes over time.
- [mongoose-diff-history](https://github.com/victorquinn/mongoose-diff-history) – Tracks changes to documents by storing only diffs between versions, enabling lightweight versioning and audit trails.

---

## 📎 File & Media Handling
- [mongoose-attachments](https://github.com/heapsource/mongoose-attachments) – Adds file attachment support for Mongoose models with multiple storage backends (S3, GridFS, local) and automatic image transformations.

---

## 🎁 Miscellaneous
- [mongoose-delete](https://github.com/dsanel/mongoose-delete) – Soft delete with restore and query helpers.
- [mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) – Transparent field-level encryption.
- [mongoose-fuzzy-searching](https://github.com/VassilisPallas/mongoose-fuzzy-searching) – Fuzzy full-text search across multiple fields.
- [mongoose-sequence](https://github.com/ramiel/mongoose-sequence) – Auto-increment fields.
- [mongoose-history](https://github.com/nassor/mongoose-history) – Document versioning and history.

---

🔗 **Sources**: community plugins, npm, and [plugins.mongoosejs.io](https://plugins.mongoosejs.io).
