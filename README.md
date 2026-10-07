# React Dependency Sandbox

A small dependency experiment containing React and React DOM package manifests. The `my-app` entry is a Git submodule reference (gitlink), but no `.gitmodules` file provides the source repository URL. A standard clone therefore has no populated application source. The root package manifest has no start or build script.

For the quiz application source, see [Phase 2](https://github.com/amiralimgh7/web-phase-2-front), [Phase 3](https://github.com/amiralimgh7/Web_Fall1403_Phase3_FE), or [Phase 4](https://github.com/amiralimgh7/Web_Fall1403_Phase4_FE).

## Contents

- `package.json`: dependency declarations.
- `package-lock.json`: npm dependency lockfile.
- `my-app`: an unconfigured Git submodule reference.

Run `npm ci` if you need to reproduce this dependency snapshot. Dependencies are generated locally and excluded from version control.
