# Changelog

## [0.2.0] - 2026-08-03

### Added

- 统一为 publisher 角色命名
- 同步 Creator 与 Distiller 的发布交接名称

## 0.1.1

- Add Alipay SkillPay as a first-class adapter with explicit package, upload,
  review, and live completion gates.
- Make WorkBuddy Skill Kit modules self-contained by copying shared resources and localizing `$KIT_DIR` references in standalone module packages.
- Preserve the full SemVer suffix when deriving a Connector ZIP name from an output directory such as `v0.2.0`.

## 0.1.0

- Add an independent multi-channel publishing workflow for validated local Skills.
- Support LovStudio source, release, catalog, revalidation, and live verification.
- Support external-profile WorkBuddy Connector packaging and import evidence.
- Keep channel metadata and generated artifacts outside canonical Skill source.
- Define a provider adapter contract for future official distribution channels.
