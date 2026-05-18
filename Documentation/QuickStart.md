# XRCore AI Quick Start

This guide gets `com.xrcore.ai` running quickly in a clean Unity project.

## Prerequisites

- Unity `6000.3` or newer.
- `com.xrcore.sdk` installed.

## Setup

1. Import XRCore SDK.
2. Import XRCore AI.
3. Confirm the project compiles with no errors.

## First runtime validation

1. Enter Play mode.
2. Query descriptors:
   - `XRCapabilityRegistryRuntime.GetRegisteredDescriptors()`
3. Execute:
   - `ai.system.ping` (expect success and `pong`)
   - `ai.registry.list` (expect serialized registry content)

## Next step

For external tool exposure, install `xrcore-ai-mcp`.
