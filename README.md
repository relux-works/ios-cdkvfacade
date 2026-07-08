# CoreDataKVFacade

A simple facade for CoreData with built-in Key-Value storage implementation. Syncs nicely with CloudKit through NSPersistentCloudKitContainer.



## CDKVFacadeSample

A sample app that demostrates the use of the facade.

Edit `CDKVFacadeSample.xcodeprojless` manifest to specify:

- your Development Team ID
- random iCloud container
- random boundle identifier


```
Root -> settings -> base -> DEVELOPMENT_TEAM
```

```
Root -> targets -> app-ios -> entitlements -> properties -> com.apple.developer.icloud-container-identifiers
```

```
Root -> settings -> base -> PROJECT_BUNDLE_ID_PREFIX
```



Use [Xcodegen](https://github.com/yonaskolb/XcodeGen) to generate the Xcode project:

```
cd path/to/package/directory
```

```
./.xcgen
```


## ToDo:

- [ ] observe db changes to propagate updates to UI in real time
- [ ] background updates

<!-- relux-ecosystem:start -->

## About Relux Works

This project is part of the open-source ecosystem of
[Relux Works](https://relux.works), an AI-native software development studio.
We build fixed-price MVPs, rescue vibe-coded apps, run local AI inference, and
train teams to work with coding agents — and we open-source much of the
infrastructure behind it.

- Full catalog: [relux.works/en/open-source](https://relux.works/en/open-source/)
- Agentic enablement: [agent harnesses & team training](https://relux.works/en/agentic-enablement/)
- Hire us the agent-native way — point your assistant at `https://api.relux.works/mcp`
- Contact: ivan@relux.works

<!-- relux-ecosystem:end -->
