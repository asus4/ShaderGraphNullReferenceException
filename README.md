This is a simple project to reproduce the NullReferenceException error in the Shader Graph.

## How to reproduce

1. Press "Play" button in Unity Editor.
2. Stop playing
3. Try to crate a new node in the Shader Graph
    - Both "right click" and "space" will throw the error.

https://user-images.githubusercontent.com/357497/220766749-6bd81e67-1894-49ec-9c4d-3204d6f5e072.mp4

---

- [Unity Forum Thread](https://forum.unity.com/threads/shader-graph_searchwindowprovider-create-node-causes-null-reference-exception-error.1391104/)
- [Issue Tracker](https://issuetracker.unity3d.com/issues/shader-graph-new-node-is-not-created-and-the-nullreferenceexception-object-reference-not-set-to-an-instance-of-an-object-error-is-printed-when-pressing-create-node-after-entering-and-exiting-play-mode)
