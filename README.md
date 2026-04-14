# Training-Collection (Setups for Training Events)

This repository contains all necessary training material
(virtual machine infrastructure and training modules)
for the training modules delivered at different training events.

Each training event is identified with a slug (short name)
that serves as the branch name of this collection for the event.

Use the
[`bootstrap_...` script](https://github.com/epics-training/training-vm/blob/main/doc/creating-vm-from-scratch.md#get-and-run-the-bootstrap-script)
to check it out on your VM instance.
Leave the training event slug empty to check out
the default branch of the collection
(usually pointing to recent versions of all submodules).

You can run the `update.sh` script at any time
to update your instance to the latest versions of all modules.

This repository works as a parent for the other modules
in the epics-training organization,
which are linked as git submodules.

## Valid training event slugs / branches

| Slug                | Training                                            |
| ----                | --------                                            |
| &lt;empty&gt;       | &lt;main branches of everything for development&gt; |
| 2024-spring-pohang  | EPICS Collab. Meeting April 2024 in Pohang          |
| 2024-fall-oakridge  | EPICS Collab. Meeting September 2024 in Oak Ridge   |
| 2025-spring-harwell | EPICS Collab. Meeting April 2025 on Harwell campus  |
| 2026-spring-saclay  | EPICS Collab. Meeting April 2026 in Saclay          |
