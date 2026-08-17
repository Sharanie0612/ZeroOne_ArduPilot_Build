# ZeroOne ArduPilot Build

Public GitHub Actions workflow for building firmware from
[`Sharanie0612/ardupilot`](https://github.com/Sharanie0612/ardupilot).

The workflow is intentionally kept separate from the ArduPilot fork so the
fork can stay aligned with `ArduPilot/ardupilot`. Builds are started through
the ZeroOne desktop compiler or manually from the Actions page.

## Security

- Only `workflow_dispatch` is enabled; pull requests and pushes do not start builds.
- The workflow has read-only repository contents permission.
- Do not commit GitHub tokens or Feishu credentials. Configure optional
  notification credentials as repository Actions secrets.
