# What's New

## dotTrace 2019.2

* Timeline filters in Rider. <br>
  dotTrace in Rider becomes more mature: Now, it gets the full set of Timeline filters making it easier to analyze Timeline profiling napshots in place.

* .NET Core 3.0 full support.<br>
  dotTrace is now able to attach to the .NET Core 3.0 Preview 7 processes.

* Improved support for ASP.NET Core applications in Visual Studio:
  * different hosting models are correctly supported,
  * browser settings and Enable SSL are taken into account when starting a profiling session,
  * ASP.NET Core 3.0 Preview 7 is supported,
  * and other improvements...

* Profiling API gets the ability to detach from the profiled process.

* Silverlight and WebDev applications are no longer supported.

## dotTrace 2019.1

* Mono and Mono Unity applications support:
  * Standalone dotTrace: Windows only.
  * dotTrace integrated into JetBrains Rider: Windows, macOS, and Linux.

* Command-line profiler improvements:
  * The start and attach commands now accept advanced profiling parameters, like time measurement type and others.
  * The Reporter.exe tool accepts the --save-signature argument that allows you to distinguish overloaded methods in the final report.

* New profiling API. We have significantly updated the profiling API:
  * we got rid of the state machine. Now, you can call any API method regardless of the controller state.
  * we have reduced the number of available methods, thereby simplifying the use of the API.
  * now, we distribute the API as a NuGet package.

## dotTrace 2018.3

* JetBrains Rider integration. You can configure and run profiling sessions, get snapshots, and analyze them in the built-in viewer. Note that currently the viewer cannot show distribution of events on a timeline. That's why timeline snapshots are opened as simple sampling snapshots.

* Improved .NET Memory Allocations filter. Timeline Viewer gets a new subfilter that allows you to analyze how the allocated memory is distributed between the objects of a certain type.

* Reworked IIS Express profiling settings. Now, the default way to profile a web app hosted on IIS Express is to provide dotTrace a applicationhost.config file.

## dotTrace 2018.2

* Improved performance and stability.

* Include filters for .NET processes. When configuring profiling of an arbitrary .NET process, you are able to set an include filter: dotTrace will attach only to the process that matches the filter.

## dotTrace 2018.1

* Improved performance. This release of dotTrace was mainly focused on improving stability and performance.

## 

work id: 9068
ip: 10.139.22.60
