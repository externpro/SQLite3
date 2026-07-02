# SQLite3 dependencies

|project|license [^_l]|description [dependencies]|version|source|diff [^_d]|
|-------|-------------|--------------------------|-------|------|----------|
|<a id='SQLite3' />[SQLite3](https://www.sqlite.org/index.html 'SQLite website')|[SQLite](https://www.sqlite.org/copyright.html 'public domain dedication - no license required')|C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine [deps: _Threads_]| |[upstream](https://github.com/azadkuh/sqlite-amalgamation 'github.com/azadkuh/sqlite-amalgamation')|  [patch]|
|<a id='Threads' />[Threads](https://cmake.org/cmake/help/latest/module/FindThreads.html)|[LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html 'GNU Lesser General Public License v2.1 or later')|Finds and determines the thread library of the system for multithreading support|[xpv1.0.4](https://github.com/externpro/Threads/releases/tag/xpv1.0.4 'release')|[repo](https://github.com/externpro/Threads 'github.com/externpro/Threads')|[diff](https://github.com/externpro/Threads/compare/v0...xpv1.0.4 'github.com/externpro/Threads/compare/v0...xpv1.0.4') [bin]|

![deps](xprodeps.svg 'dependencies')

Dependency version check: all 1 parent-manifest versions match pinned versions.

|diff  |description|
|------|-----------|
|patch |diff modifies/patches existing cmake|
|intro |diff introduces cmake|
|auto  |diff adds cmake to replace autotools/configure/make|
|native|diff adds cmake but uses existing build system|
|bin   |diff adds cmake to repackage binaries built elsewhere|
|fetch |diff adds cmake and utilizes FetchContent|

[^_l]: see [SPDX License List](https://spdx.org/licenses/ '') for a list of commonly found licenses
[^_d]: see table above with description of diff
