# Coding notes

Just setting up

## Bit more
 * Hello 

 **Hello**

 ***Hello***

List
1. Item
2. Item
3. Item

* Item
* Item
* Item

> CTRL + SHIFT + P

Create Ground from Babylon

```Javascript
Js
function createGround(scene: Scene) {
  const groundMaterial:StandardMaterial = new StandardMaterial("groundMaterial");
  groundMaterial.diffuseTexture = new Texture("./src/assets/textures/wood.jpg");
  groundMaterial.diffuseTexture.hasAlpha = true;
  groundMaterial.backFaceCulling = false;
  let ground: GroundMesh = MeshBuilder.CreateGround(
    "ground",
    { width: 15, height: 15, subdivisions:4 },
    scene
  );

  ground.material = groundMaterial;
  return ground;
}
```
This code does this using the [NameOfFunction] function to make the object interact in a certain way

[Markdown notes](https://derekturner.github.io/Javascript-Games-Fund-24/#/Block_1/section_6/markdown)

This website helped me understand how to do this

![markdown](BabylonProj/Images/md.png)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

---

End of Test