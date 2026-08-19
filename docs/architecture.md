# TabLoop repository architecture

Local workspace:

```text
TabLoop/
├─ tabloop-android/        # Private Git repository
└─ tabloop-autoclicker/    # Public Git repository
   ├─ pc-agent/
   ├─ assets/
   ├─ docs/
   └─ index.html
```

`TabLoop/` itself is only a local workspace folder and should not be a Git repository.
