# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project aims to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## <Version> (<Release date>)
### Fixes

### Changes

### Additions

### Removals

## 3.7.0 (Thursday, 22 July 2021)
### Added
- Allow installation of spatie/dto 3 [#285]((https://github.com/knuckleswtf/scribe/pull/285))

## 3.6.3 (Tuesday, 20 July 2021)
### Fixed
- Stop Validator::make parsing from crashing unnecessarily [#281]((https://github.com/knuckleswtf/scribe/pull/281))

## 3.6.2 (Saturday, 17 July 2021)
### Fixed
- Encode Postman collection items correctly (fixes #278)([87b99bc717f541d6a4d2925fc7bc544958451d12](https://github.com/knuckleswtf/scribe/commit/87b99bc717f541d6a4d2925fc7bc544958451d12),

## 3.6.1 (Friday, 16 July 2021)
### Fixed
- Use correct asset path (fixes #274)([00b77e4b144e13b579e5ad820ab79a1b42eac756](https://github.com/knuckleswtf/scribe/commit/00b77e4b144e13b579e5ad820ab79a1b42eac756),

## 3.6.0 (Tuesday, 13 July 2021)
### Fixed
- Sort group filenames numerically (fixes #273)([c77fed23f04ab1f13bb06bf5b099227ced46dbdc](https://github.com/knuckleswtf/scribe/commit/c77fed23f04ab1f13bb06bf5b099227ced46dbdc),

## 3.5.2 (Monday, 12 July 2021)
### Modified
- Internal change: refactor RouteDocBlocker (https://github.com/knuckleswtf/scribe/pull/272)

## 3.5.1 (Tuesday, 6 July 2021)
### Fixed
- Try It Out: Turn off autocomplete; make sure it works for array body; improve UI spacing ([579f672b57ad0417a5563aee1621b84c3b4ff1f2](https://github.com/knuckleswtf/scribe/commit/579f672b57ad0417a5563aee1621b84c3b4ff1f2), [2af8d8eacd661e0601b2d6f4dbc1766bf75e702a](https://github.com/knuckleswtf/scribe/commit/2af8d8eacd661e0601b2d6f4dbc1766bf75e702a))

## 3.5.0 (Monday, 5 July 2021)
### Modified
- Get URL parameter name from field bindings (https://github.com/knuckleswtf/scribe/commit/ce6be7ca68ed0e682258eca5bbeb2f7d84774714)

## 3.4.3 (Monday, 5 July 2021)
### Modified
- Internal change: switch to using strategies to get "grouped endpoints" (https://github.com/knuckleswtf/scribe/pull/263)

## 3.4.2 (Monday, 5 July 2021)
### Modified
- Only use model key type for URL param type if it's the same as the route key name (https://github.com/knuckleswtf/scribe/pull/265)
### Fixed
- Merge user-defined endpoints correctly. (https://github.com/knuckleswtf/scribe/commit/b7f8539b1bd5cd4d97496fa93803a3d7894889f6)

## 3.4.1 (Friday, 2 July 2021)
### Fixed
- Set nested file fields properly in Postman. (https://github.com/knuckleswtf/scribe/commit/39d53eac5db30c1d4b6b16cff836c1d3a3898f89)

## 3.4.0 (Thursday, 1 July 2021)
### Added
- Support better examples based on the `where` clause in routes. (https://github.com/knuckleswtf/scribe/commit/cf2b53c16d405e655886b6225e9ebbf29a6621a8)

### Fixed
- Correctly generate params and description for explicit field bindings in routes (https://github.com/knuckleswtf/scribe/commit/b0b89195e6ce0333cf07573462fa9ec083d04f4d)
- Fix content-type header not showing (https://github.com/knuckleswtf/scribe/commit/d5a7b6d8be9f257df3146cd6026729232aa63f1e)
- Try It Out: Spoof HTTP method for PUT/PATCH requests (https://github.com/knuckleswtf/scribe/pull/257)

## 3.3.2 (Wednesday, 30 June 2021)
### Fixed
- Try It Out: Add cancellable requests (https://github.com/knuckleswtf/scribe/commit/816e6fbd37ead033ca58bad048f38455622cb0b9)
- Try It Out: Restore sample request/response after cancel (https://github.com/knuckleswtf/scribe/commit/25aaabbea3a4b0482e510932cc095c8ce9495427)
- Try It Out: set FormData content-type properly (https://github.com/knuckleswtf/scribe/pull/249)

## 3.3.1 (Tuesday, 29 June 2021)
### Fixed
- Set nested file parameters properly in examples (https://github.com/knuckleswtf/scribe/commit/6354b5592d1e042fe627894156ff17a684fce667)

## 3.3.0 (Friday, 25 June 2021)
### Fixed
- Don't depend on unavailable view service provider (https://github.com/knuckleswtf/scribe/pull/254)
- Delete older versioned assets (https://github.com/knuckleswtf/scribe/commit/b02af7e21f89406ec33be2e6ca1c206df3733b1b)
- Generate proper OAS types for files and request body arrays (https://github.com/knuckleswtf/scribe/commit/8b51d839d213a1abe110e439281273b33facb344)

### Modified
- Exclude more specific headers from sample responses (https://github.com/knuckleswtf/scribe/commit/5583b725d714090a198cf906115860626f537c09)

## 3.2.0 (Thursday, 24 June 2021)
### Added
- Support simple key-value for response headers (https://github.com/knuckleswtf/scribe/commit/20afb7e10ca8c5616fd5b9ce1b5333739fdd2348)

### Modified
- Throw helpful error if factory instantiation errors (https://github.com/knuckleswtf/scribe/commit/5eb0d72f9b2898702c14d28582195722c27f00d0)

## 3.1.0 (Friday, 18 June 2021)
### Added
- Support nullable and union responseField types (https://github.com/knuckleswtf/scribe/commit/2912ac2344b37e30599aa1004c90e146a6f76aaa)

### Fixed
- Fix OAS generation (https://github.com/knuckleswtf/scribe/commit/a5f51714eafe9b281cc1bbeb1b3186c03f4e3e61)

## 3.0.3 (Friday, 18 June 2021)
### Fixed
- Try It Out: Send body params in the right format (https://github.com/knuckleswtf/scribe/pull/245)

## 3.0.2 (Friday, 11 June 2021)
### Fixed
- Use regular relative paths for assets if not using default static output path (https://github.com/knuckleswtf/scribe/commit/05aaba1877e9ca3dbf7a130dcbd12a2ba9438136)

## 3.0.1 (Tuesday, 8 June 2021)
### Fixed
- Properly cast status codes for API Resource and Transformer responses (https://github.com/knuckleswtf/scribe/pull/235)
- Don't crash on unrecognized validation rule formats (https://github.com/knuckleswtf/scribe/commit/c86ea65e903a013f33dc660269d7fff5e2376490)

## 3.0.0 (Monday, 7 June 2021)
[Release announcement](https://scribe.knuckles.wtf/blog/2021/06/08/laravel-v3)