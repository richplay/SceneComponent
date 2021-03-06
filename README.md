# SceneComponent
![](https://img.shields.io/badge/Unity-2018.1-blue.svg?style=flat-square) ![](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

Unity plugin to put components to a scene like game object

# Getting Start

Just add this plugin to your unity project. That all :)

# Usage

To add components to scene, just drag and drop as game object does.

![scene-component-usage](https://user-images.githubusercontent.com/18159012/42412632-d165c056-824a-11e8-95df-4637361cdd09.gif)

To get scene components try below.

```c#
public void Start() {
    NewBehaviour[] newBehaviourList = SceneEntity.GetComponents<NewBehaviour>();
    NewBehaviour newBehaviour = SceneEntity.GetComponent<NewBehaviour>();
}
```

For now `SceneEntity` class return components that of latest loaded scene.