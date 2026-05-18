# XRCore AI Capability Layer

[![Unity](https://img.shields.io/badge/Unity-2022%2B%20%7C%20Unity%206-black)](https://unity.com/)
[![Module](https://img.shields.io/badge/Module-AI%20Capability%20Layer-2563eb)](#)
[![Depends](https://img.shields.io/badge/Depends-XRCore%20SDK-7a3cff)](https://github.com/splibiplay/xrcore-sdk)
[![Architecture](https://img.shields.io/badge/Architecture-Domain%20Agnostic-0ea5e9)](#)

`com.xrcore.ai` is the neutral AI capability layer for XRCore modules.

## Published foundation (Unity Asset Store)

Install the core SDK from Unity first, then add this module via Git URL:

- [XRCore – Event-Driven AI Framework for Unity XR](https://assetstore.unity.com/packages/tools/ai-ml-integration/xrcore-event-driven-ai-framework-for-unity-xr-366852)

## Value in 2 Minutes

1. Import XRCore SDK + XRCore AI.
2. Enter Play mode.
3. Query `XRCapabilityRegistryRuntime.GetRegisteredDescriptors()`.
4. Invoke:
   - `ai.system.ping`
   - `ai.registry.list`

## What It Adds

- Capability contracts (`IXRToolCapability`, `IXRCapabilityProvider`, `IXRCapabilityRegistry`, `IXRAgentSessionStore`)
- Runtime registry execution API
- Session tracking API for agent/tool flows
- Built-in executable validation capabilities

## Ecosystem Position

```text
XRCore SDK
    ↓
XRCore AI (neutral capability layer)
    ↓
Domain modules register capabilities
    ↓
Adapters (MCP and future adapters) expose tools externally
```

## Related XRCore Modules

[![Hub — splibiplay](https://img.shields.io/badge/Hub-splibiplay-24292f?style=flat-square)](https://github.com/splibiplay/splibiplay)
[![Unity Asset Store — XRCore](https://img.shields.io/badge/Unity%20Store-XRCore-f59e0b?style=flat-square)](https://assetstore.unity.com/packages/tools/ai-ml-integration/xrcore-event-driven-ai-framework-for-unity-xr-366852)

[![xrcore-sdk](https://img.shields.io/badge/GitHub-xrcore--sdk-2563eb?style=flat-square)](https://github.com/splibiplay/xrcore-sdk)
[![xrcore-context](https://img.shields.io/badge/GitHub-xrcore--context-0e7490?style=flat-square)](https://github.com/splibiplay/xrcore-context)
[![xrcore-training-toolkit](https://img.shields.io/badge/GitHub-training--toolkit-7c3aed?style=flat-square)](https://github.com/splibiplay/xrcore-training-toolkit)
[![xrcore-assessment](https://img.shields.io/badge/GitHub-assessment-db2777?style=flat-square)](https://github.com/splibiplay/xrcore-assessment)
[![xrcore-training-authoring](https://img.shields.io/badge/GitHub-authoring-c2410c?style=flat-square)](https://github.com/splibiplay/xrcore-training-authoring)
[![xrcore-voice](https://img.shields.io/badge/GitHub-voice-059669?style=flat-square)](https://github.com/splibiplay/xrcore-voice)
[![xrcore-visionplus](https://img.shields.io/badge/GitHub-vision--plus-0f766e?style=flat-square)](https://github.com/splibiplay/xrcore-visionplus)
[![xrcore-llbridge](https://img.shields.io/badge/GitHub-llbridge-4f46e5?style=flat-square)](https://github.com/splibiplay/xrcore-llbridge)
[![xrcore-analytics](https://img.shields.io/badge/GitHub-analytics-d97706?style=flat-square)](https://github.com/splibiplay/xrcore-analytics)
[![xrcore-ai](https://img.shields.io/badge/GitHub-xrcore--ai-9333ea?style=flat-square)](https://github.com/splibiplay/xrcore-ai)
[![xrcore-ai-mcp](https://img.shields.io/badge/GitHub-xrcore--ai--mcp-7c3aed?style=flat-square)](https://github.com/splibiplay/xrcore-ai-mcp)

## Documentation

- [QuickStart](Documentation/QuickStart.md)
- [Changelog](Documentation/CHANGELOG.md)
- [Third-Party Notices](Documentation/THIRD_PARTY_NOTICES.md)

## Support

- Email: `support@xrcore.dev`
- Website: `https://xrcore.dev`
