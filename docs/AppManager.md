---
layout: default
---

## Blu Cow App Manager

<br/>

<a href="https://github.com/aemsle/Team-Blu-Cow-App-Manager">Project Source</a>

```cs
private void Start()
{
   blu.App.AddModule<TestModule>();
   blu.App.GetModule<TestModule>().DoSomething();
}
```

* * *

This was created to make setting up unity projects for game jams easier. This manager is a wrapper around the lifetime of singletons in a unity project that has a simple API for instantiating managers and clearing them when they're no longer needed.

[back](./)
