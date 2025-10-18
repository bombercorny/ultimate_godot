# ultimate_godot

## Notes
### Frogger
- elements can be dragged and dropped to the 2d canvas from the filesystem folder
    - this will add a 2d node to the sceen (left side)
    - using the inspector on the right side specific properties of the node can be updated

- but instead use scenes on the 2d screen by adding nodes

### Scenes & Nodes
**Nodes**
- basic building blocks
- images, timers, etc

**Scenes**
- containers for Nodes
- manage whats displaed in the game
- scene can be a whole level

#### First Example
1. Create Root Node 2d
2. Add ChildNode Sprite2d
3. Add a texture to the Sprite2d node
    - drag and drop the godot icon to the texture in the inspector of the Sprite2d
4. Optionally copy the Sprite2d node to create additional nodes
    - change the visiblity of additional nodes to differentiate

> Nodes in a scene are related to each other. Therefore rotating the FirstScene root node (parent node) will also rotate its child nodes. 