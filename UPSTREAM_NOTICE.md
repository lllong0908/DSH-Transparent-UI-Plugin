# Upstream notice and attribution

This repository is a compatibility update of **DSH-Transparent-UI-Plugin**.

## Original project

- Author: `du-u-uck`
- Repository: https://github.com/du-u-uck/DSH-Transparent-UI-Plugin
- License: GNU Affero General Public License v3.0

## Prior DSH adaptation

- Author: `WYH66666666`
- Repository: https://github.com/WYH66666666/DSH-Transparent-UI-Plugin

## Compatibility update in this repository

- Publisher: `lllong0908`
- Repository: https://github.com/lllong0908/DSH-Transparent-UI-Plugin
- Target: DeepSeek Harness `0.1.5-rc.2`

## Changes made

- Replaced the removed `@deepseek-ai/dsh-client-runtime/client` client dependency with `@deepseek-ai/dsh-client-store`.
- Restored `ctx.settingsScope.bind({ namespace: 'settings.aqua' })`.
- Updated `settings.plugin.item` to the current keyed registration model.
- Registered settings surfaces with `ctx.slots.inject(...)`.
- Updated package metadata and generated type declarations.

This repository remains distributed under the AGPL-3.0 license included in `LICENSE`. The upstream authorship notices must not be removed from redistributed copies.
