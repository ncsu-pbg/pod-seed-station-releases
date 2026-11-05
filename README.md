# Pod & Seed Station — releases

Release files for the OAK4 pod and seed grading station (**PodSeedStation**)
built by NC State Peanut Breeding & Genetics. This repository holds
**releases only**; no source code lives here.

Each release (see the *Releases* tab) contains:

| File | What it is |
|---|---|
| `manifest.json` | the index a station reads: channel, versions, SHA-256 and size of every file, release notes |
| `PodSeedStation-<version>.exe` | the station program (Windows) |
| `pod-counter-<version>-pod.oakapp`, `-seed.oakapp` | camera packages for the pod and seed cameras (only when the camera software changed) |
| `oakctl.exe` | Luxonis' camera tool, shipped with permission |

A station checks `releases/latest/download/manifest.json` on its own
schedule, verifies every file against the manifest, and offers the
update on its **Updates** card. Operators at partner sites do not need
anything from this page; the station handles it.

Questions: NC State Peanut Breeding & Genetics.
