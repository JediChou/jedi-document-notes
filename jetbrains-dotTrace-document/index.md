# dotTrace 2019.2

* [Introduction](/part1/Introduction.md)
  * [What's New](/part1/dotTrace_Whats_New.md)
  * Basic Concepts
    * Profiling Workflow Overview
    * Profiling Methods Overview
      * Performance Profiling
        * Profiling Types
        * Time Measurement Methods
      * Timeline Profiling

* How To
  * Get Started with Performance Profiling
  * Get Started with Timeline Profiling
  * Find the Cause of a UI Freeze
  * Optimize App Performance and Memory Traffic
  * Profile Standalone Application
  * Profile Running Process
  * Profile Web Application in IIS Express
  * Profile Web Application on IIS Server
  * Profile .NET Core Application
  * Profile WCF Service
  * Profile Windows Service
  * Profile .NET Process
  * Profile XBAP Application
  * Profile Unit Test
  * Profile Static Method
  * Profile Mono Application
  * Profile Unity Application

* Running dotTrace

* Working with Standalone dotTrace
  * Starting Local Profiling Session
  * Starting Remote Profiling Session
  * Starting Recent Profiling Session
  * Basic Operations with Snapshots
    * Opening Snapshots
    * Specifying Location for Storing Snapshots
    * Deleting Snapshots
    * Auto-Deleting Snapshots
    * Copying Snapshots to Another Computer
    * Adding Annotations to Snapshots

* Working with dotTrace Integrated in Visual Studio
  * Starting Local Profiling Session
  * Basic Operations with Snapshots

* Working with dotTrace Command-Line Profiler

* Configuring Profiling Session
  * Application Options
    * Standalone Applications
    * .NET Core Applications
    * Web Applications Using IIS
    * Web Applications Using IIS Express
    * Windows Services
    * WCF Services
    * WinRT Applications
    * .NET Processes
    * Mono Applications
    * Unity Applications
  * Profiler Options

* Controlling Profiling Session

* Controlling Profiling Session Through API
  * API Reference

* Analyzing Performance Profiling Results
  * Choosing the Right View for Snapshot Data
    * Overview
    * Threads Tree
    * Call Tree
    * Plain List
    * Hot Spots
    * Back Traces
  * Finding Application Bottlenecks
    * Studying Function Timings
    * Finding Out Frequency of Function Calls
  * Identifying and Narrowing an Area of Interest
    * Opening a Function or a Class in a New Tab
    * Creating and Applying Filters
    * Folding Filtered Calls
    * Folding Recursive Calls
    * Folding Calls with a Small Impact
    * Hiding Functions that Consume Zero Time
    * Color-Coding Functions
  * Simplifying Analysis with Subsystems
  * Forecasting Performance
  * Navigation and Search
    * Navigating Between Function Calls
    * Searching for Functions
    * Bookmarks
  * Labeling and Formatting
    * Formatting Functions
    * Adding Annotations
  * Previewing Source Code
    * Configuring Path to Source Files
    * Navigating from dotTrace Source Preview to Visual Studio
    * Source View and Line-by-Line Profiling
  * Comparing Profiling Data
  * Sharing Snapshot Data

* Analyzing Timeline Profiling Results
  * Timeline Viewer Concepts
  * Timeline Window
    * Process Overview
    * Threads Diagram
  * Filters
    * Events
      * Not Selected
      * .NET Memory Allocations
      * Unreleased Native Allocations
      * Debug Output
      * Garbage Collection
      * Exceptions
      * JIT Compilation
      * File Operations
      * SQL Queries
    * Thread State
      * Running
      * Waiting
    * Interval Filters
      * UI Freeze
      * Incoming HTTP Requests
      * Tasks
    * Subsystems
  * Call Stack
    * Methods and Subsystems
    * Call Tree
      * Analyzing Async Calls
      * Forecasting Performance
      * Folding Calls
      * Configuring the List of System Modules
  * Events
  * Source View
    * Configuring Path to Source Files
    * Navigating from Source View to Visual Studio

* Reference
  * Specifying License Information
  * Home Window
  * Performance Viewer
    * Legend
    * Keyboard Shortcuts
  * Timeline Viewer
    * Legend
    * Keyboard Shortcuts
  * Timeline Viewer in Visual Studio
    * Legend
    * Keyboard Shortcuts
  * Dialogs
    * Add/Edit Line-by-line Filter
    * Edit Symbol Search Policy
    * License Information dialog
    * Obtain Permanent License dialog
    * Profiling Filters
    * Add/Edit Formatting
    * Adjust Time
    * Bookmarks
    * Properties
    * Subsystem Definition
  * Options
    * General
    * Environment
      * Product Feedback
      * Web Proxy Settings
    * View
    * Folding
      * System Module Folding
    * Subsystems
      * Profiles
    * Source Preview
      * Decompiler
      * Folder Substitutions
      * Symbol Server Integration
  * Third-Party Software Shipped with dotTrace
  * Integrating dotTrace with Typemock Isolator
