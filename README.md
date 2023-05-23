# Open-source engine projects for profiling
By Gabriel C. Ullmann, 2023.

## How we use these projects
- BaseGame: an "empty" project with one scene and nothing else. When run with Callgrind, it allows us to see the call graph of Godot "core" without the interference of other feature-specific calls.
- Pong: a sample project we intend to compare to the empty project in the future.

## Profiling Results
Here you can see examples of .out files generated by Callgrind and trees drawn by KCacheGrind:
- Godot projects: empty, pong
- "Hello world" projects: hello-c, hello-java
- Other game engine projects: minestest, shervanator, urho3d


