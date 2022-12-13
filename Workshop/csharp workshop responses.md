# What do you remember from today?

* SourceLink
* Doubles are base2, humans and decimal are base10 math
* Warnings can be filtered in VS (funnel in the table header)
* Records are not a good fit for my application - because I don't need structural/value equality
* Use patterns to reduce total number of lines of code, less code is more readable (most of the time)
* New switch expressions!
* Arithmetic Overflow (and how you can control it via project properties and `checked` keyword)
* tuple switch patterns
* NuGet Package Source Mapping can be used to specify allowed feeds for packages
* Switch expressions!
* Switch expressions (again!)
* "I don't know math anymore" - stuff's hard, folks.
* "All math should be done with decimals" 
* TreatWarningsAsErrors can prevent re-introducing warnings. Check box in project properties (or raw project file) (or CLI argument)
* Reference types on heap, value types on stack
* NuGet packages allow READMEs now
* Enable Nullability checking (on new projects) (when you can)!
* Ints implicitly widen (such as Int16 => Int32)
* using `checked` to be explicit about overflow/underflow
* Don't use new DateTime to do math - you _will_ get it wrong!
* `throw` can be an expression
* Project Properties can help customize your NuGet Package
* local functions are pretty cool - they help organize algorithms
* pattern matching is flexible - all patterns are listed in docs (C# patterns -> learn.microsoft.com)
* BenchmarkDotNet for micro-benchmarks (`time` in a loop just doesn't cut it). VS also has a profiler.
* build metadata properties (x2) can be used to add features to the NuGet.org UI (readme, prefix, release notes, license)
* string interpolation/raw string literals (check it out on learn.microsoft.com or https://www.youtube.com/watch?v=4KXWAgZE8xI)
* Infinity is a legitimate answer as is NaN
* .NET SDK 7 supports packaging an app as a container image - use the Microsoft.NET.Build.Containers package.
* The type of the operands determine the type of division done (integer vs fractional)
* Local Directory NuGet Feeds can serve internal company packages
* Example Repos from speakers are helpful for attendees
* NuGet global packages location exists and needs clearing sometimes
* Record comparison is _fast_ (for value equality) because they don't use reflection.
* Decimals are preferred for math, but are slower
* Company NuGet prefixes can be reserved (for security)
* Spectre.Console is an awesome package, as are all of Patrik Svensson's tools
* Structured Log Viewer is helpful for digging into builds
* Build Log argument (-bl) can be used to generate logs to use in ^
* Boxing - would be nice if there were more warnings when it happens
* File scoped namespaces help save space