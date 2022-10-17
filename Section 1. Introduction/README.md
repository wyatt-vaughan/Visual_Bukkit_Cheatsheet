# Section 1. Introductiom
Welcome to the Visual Bukkit Cheatsheet, if you have any questions/concerns/comments leave it under the Issues tab.
## What is Visual Bukkit
Visual Bukkit is a visual programming language for Bukkit plugins, allowing you to create plugins without knowing Java. Using code from both Spigot and Custom VB blocks, you can create nearly anything you can dream of. With vibrant colors and quick snapping nodes and blocks, learning to make amazing bukkit plugins is only a couple clicks away.

## Common Uses
Visual Bukkit can be used to create anything but some things are just easier to find a plugin that already exsists. Visual Bukkit is made for adding small changes to already simple plugins. Some examples of plugins made with VB are...
1. 
2.
3.

## Reading this document
As Visual Bukkit changes the UI this section will update how to interpret the rest of the Visual Bukkit Cheatsheet

---

![image](https://user-images.githubusercontent.com/69369798/196063075-17565492-e5a4-4e7f-9915-18d5f7e4d510.png)

```
[Bukkit] Broadcast Message =>
    Message: This is a Message
```

---

![image](https://user-images.githubusercontent.com/69369798/196062181-137225be-9b27-46e5-bfd2-96213db0cff2.png)

```
[Bukkit] Command =>
    Name: parameter
    Aliases: another parameter
    Permission: this one too
```

---

![image](https://user-images.githubusercontent.com/69369798/196091241-9e5fdc7a-834d-4b23-a5ff-a138bee613f4.png)

```
[Block] Set Type =>
    Block: [Location] Get Block =>
        Location: [Location] New Location =>
            World: [Bukkit] Get World =>
                Name: over_world
            X: 100
            Y: 50
            Z: -100
    Type: [Material] GOLD_BLOCK
```

---

![image](https://user-images.githubusercontent.com/69369798/196063577-f5f0e695-855b-4450-b6b9-720f511724da.png)

```
[Event] PlayerInteractEvent =>
	Priority: NORMAL
[VB] If Statement =>
	Condition: [VB] Is Equal =>
		Object: [PlayerInteractEvent] Get Material
		Object: [Material] GOLD_BLOCK
	Mode: NORMAL
	[HumanEntity] Set Item In Hand =>
		HumanEntity: [PlayerInteract] Get Player
		Item: [ItemStack] New Named ItemStack =>
			Material: [Material] BOOKSHELF
			Name: BOOKIEEE
```
---

I know this looks complicated and I will try and use as many screen shots instead.
