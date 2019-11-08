# PhotonBoltStateReplicationPropertyBugRepo
Simple Unity Project showcasing state property not being saved in bolt assets editor

# Which Bolt Version?
Bolt Free Debug v1.2.10

# Which Unity Version to use?
2019.2.6f1
[download here](https://unity3d.com/get-unity/download/archive)

# Reproduction steps
0. Clone repository. Open Unity Project and Compile Bolt.
1. Open Bolt Asset Editor via Bolt->Assets. Open state "TestState" in bolt editor window.
2. Import Mecanim Modes->Replication Mode->Change "Everyone Except Controller" to "Local For Each Player"
3. Close Bolt Editor.
4. Observe no changes to project.json file.
5. Re-open Bolt Asset Editor.
6. Observe Import Mecanim Modes->Replication Mode is still set to "Everyone Except Controller"
7. Make other changes to "TestState" state properties and observe they are saved to project.json file.


# Original Forum Discussion
[link](https://forum.photonengine.com/discussion/14977/bolt-editor-state-property-changes-not-working-for-import-mecanim-modes-replication-mode#latest)
