# Awesome Mongoose Plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of plugins for [Mongoose](https://mongoosejs.com/) 🐒.  
> A collection of extensions to make your life with MongoDB easier.

---

## 📑 Contents
- [General Utilities](#general-utilities)  
- [Validation & Security](#validation--security)  
- [Pagination & Query](#pagination--query)  
- [Slug & SEO](#slug--seo)  
- [Internationalization (i18n)](#internationalization-i18n)  
- [Timestamps & Audit](#timestamps--audit)  
- [Miscellaneous](#miscellaneous)  

---

## 🛠 General Utilities
- [mongoose-autopopulate](https://github.com/mongodb-js/mongoose-autopopulate) – Automatically populates `ref` fields without calling `.populate()`.
- [mongoose-lean-virtuals](https://github.com/vkarpov15/mongoose-lean-virtuals) – Adds support for virtuals in `.lean()` queries.
- [mongoose-lean-getters](https://github.com/vkarpov15/mongoose-lean-getters) – Applies getters to `.lean()` query results.

---

## ✅ Validation & Security
- [mongoose-unique-validator](https://github.com/blakehaswell/mongoose-unique-validator) – Validates uniqueness of fields before saving.
- [mongoose-validator](https://github.com/leepowellcouk/mongoose-validator) – Wrapper for `validator.js` to use as Mongoose validators.
- [mongoose-hidden](https://github.com/mblarsen/mongoose-hidden) – Hides sensitive fields (like passwords or tokens) from `JSON.stringify()`.

---

## 📊 Pagination & Query
- [mongoose-paginate-v2](https://github.com/aravindnc/mongoose-paginate-v2) – Advanced pagination plugin for queries.
- [mongoose-aggregate-paginate-v2](https://github.com/webgangster/mongoose-aggregate-paginate-v2) – Pagination for aggregation queries.
- [mongoose-query](https://github.com/aheckmann/mongoose-query) – Simplified query builder.

---

## 🔗 Slug & SEO
- [mongoose-slug-generator](https://github.com/rammyblog/mongoose-slug-generator) – Generates unique slugs from string fields.
- [mongoose-slug-plugin](https://github.com/wolfeidau/mongoose-slug-plugin) – Supports multiple, historical, and multilingual slugs.

---

## 🌍 Internationalization (i18n)
- [mongoose-intl](https://github.com/ladjs/mongoose-intl) – Manage multilingual fields with fallback.
- [mongoose-i18n-localize](https://github.com/strongloop-community/mongoose-i18n-localize) – Simple localization for string fields.

---

## ⏱ Timestamps & Audit
- [mongoose-timestamp](https://github.com/drudge/mongoose-timestamp) – Automatically adds `createdAt` and `updatedAt`.
- [mongoose-audit](https://github.com/lykmapipo/mongoose-audit) – Document change tracking.

---

## 🎁 Miscellaneous
- [mongoose-delete](https://github.com/dsanel/mongoose-delete) – Soft delete with restore and query helpers.
- [mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) – Transparent field-level encryption.
- [mongoose-fuzzy-searching](https://github.com/VassilisPallas/mongoose-fuzzy-searching) – Fuzzy full-text search across multiple fields.
- [mongoose-sequence](https://github.com/ramiel/mongoose-sequence) – Auto-increment fields.
- [mongoose-history](https://github.com/nassor/mongoose-history) – Document versioning and history.

---

🔗 **Sources**: community plugins, npm, and [plugins.mongoosejs.io](https://plugins.mongoosejs.io).
