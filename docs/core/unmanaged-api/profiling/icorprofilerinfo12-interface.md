---
description: "Learn more about: ICorProfilerInfo12 Interface"
title: "ICorProfilerInfo12 Interface"
ms.date: "03/19/2021"
api_name:
  - "ICorProfilerInfo12"
api_location:
  - "coreclr.dll"
  - "corprof.idl"
api_type:
  - "COM"
---
# ICorProfilerInfo12 interface

 A subclass of [ICorProfilerInfo11](icorprofilerinfo11-interface.md) that provides methods to create EventPipe sessions, events, and providers.

## Methods

| Method | Description |
|------------|-----------------|
|[EventPipeStartSession Method](icorprofilerinfo12-eventpipestartsession-method.md)| Starts a profiler EventPipe session. |
|[EventPipeAddProviderToSession Method](icorprofilerinfo12-eventpipeaddprovidertosession-method.md)| Adds a provider to an existing EventPipe session. |
|[EventPipeStopSession Method](icorprofilerinfo12-eventpipestopsession-method.md)| Stops an EventPipe session. |
|[EventPipeCreateProvider Method](icorprofilerinfo12-eventpipecreateprovider-method.md)| Creates an EventPipe provider. |
|[EventPipeGetProviderInfo Method](icorprofilerinfo12-eventpipegetproviderinfo-method.md)| Gets the name of an EventPipe provider from its ID. |
|[EventPipeDefineEvent Method](icorprofilerinfo12-eventpipedefineevent-method.md)| Defines an event on an existing EventPipe provider. |
|[EventPipeWriteEvent Method](icorprofilerinfo12-eventpipewriteevent-method.md)| Writes an EventPipe event. |

## Requirements

**Platforms:** See [.NET supported operating systems](https://github.com/dotnet/core/blob/main/os-lifecycle-policy.md).

**Header:** CorProf.idl, CorProf.h

**.NET Versions:** Available since .NET 5.0

## See also

- [EventPipe Overview](../../../core/diagnostics/eventpipe.md)
- [Well Known EventProviders](../../../core/diagnostics/well-known-event-providers.md)
- [ICorProfilerCallback10 Interface](icorprofilercallback10-interface.md)
