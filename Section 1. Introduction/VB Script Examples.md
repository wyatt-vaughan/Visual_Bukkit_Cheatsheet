# VB Script Examples

![image](https://user-images.githubusercontent.com/69369798/196242446-36d4ea1e-8cdd-4c96-8c32-6374f159f3df.png)

```
[GUI] Create GUI =>
    GUI ID: gui_1
    Title: Selector
    Size: 27
    Mode: create once
[VB] Number Loop =>
	Number: 27
	[Inventory] Set Item =>
		Inventory: [GUI] Created GUI Inventory
		Index: [VB] Loop Number
		Item: [ItemStack] New Named ItemStack With Lore =>
			Material: [Material] WHITE_STAINED_GLASS_PANE
			Name: EMPTY
			Lore: [List] New List =>
				Object: [String] Hex Colored String =>
					String: &d DO NOT CLICK... you have been warned
```
