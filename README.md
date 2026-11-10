# PRAXO-CORE for PowerShell

Dedicated repository for the PowerShell implementation of PRAXO-CORE: an
embeddable, MIT-licensed agent execution kernel with policy controls,
human-in-the-loop approval, checkpoints, events, and tool calling.

- Package: `praxo-core-ps` on PowerShell Gallery
- Documentation: https://axisvela.github.io/praxo-core/languages/powershell/
- Canonical source: https://github.com/axisvela/praxo-core/tree/main/language/powershell
- Release index: https://axisvela.github.io/praxo-core/languages/registry-status/

This repository is a discovery mirror of the canonical PowerShell source. The
monorepo remains the source of truth and the release workflow source. Shared
conformance vectors are included under `spec/`.

## Install

```powershell
Install-Module praxo-core-ps
```

## Verify

Build and test instructions are in `language/powershell/README.md`. The
monorepo CI runs the C# Core, PowerShell API snapshot, and wrapper tests.

PRAXO-CORE is not a hosted model, workflow engine, identity provider, or safety
controller. Do not infer exactly-once execution, complete sandbox isolation,
production security certification, live-provider behavior, or physical safety
from this package.

MIT licensed.
