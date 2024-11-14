# The Standard Game Folder Structure
___
## SGFS: Standard Game Folder Structure.

> ### **The proper structuring of folders in game projects is a fundamental practice that can make the difference between the success and failure of a project.**

> #### Following good structuring practices from the outset can save a lot of time and effort in the long run, as well as ensuring that the project is easier to manage and expand as necessary.
---

	/MyGameProjectName
	/	scenes
	/	-	- interfaces
	/	-	.	main_menu.scn
	/	-	.	fade_in_out.scn
	/	-	.	item_inventory.scn
	/	-	.
	/	-	.
	/	-	- levels
	/	-	.	test_ground.scn
	/	-	.	level_1.scn
	/	-	.	level_2.scn
	/	-	.	level_3.scn
	/	-	.
	/	-	.
	/	-	- player
	/	-	.	character.scn
	/	-	.	character_upper_clothes.scn
	/	-	.	character_down_clothes.scn
	/	-	.
	/	-	.
	/	-	- enemies
	/	-	.	enemy_base.scn
	/	-	.	enemy_base.scn
	/	-	.
	/	-	- collectibles
	/	-	.	items.scn
	/	-	.	documents.scn
	/	-	.	coins.scn
	/	-	.
	/	-	.
	/	-	- events
	/	-	.	dialogues.scn
	/	-	.	videos.scn
	/	-	.
	/	-	.
	/	-	- utils
	/	-	.	button_menu_bar.scn
	/	-	.
	/	-	.
	/	-
>
	/	scripts
	/	-	- UI
	/	-	.	main_menu.c*
	/	-	.	fade_in_out.c*
	/	-	.	item_inventory.c*
	/	-	.
	/	-	.
	/	-	- management
	/	-	.	save_load.c*
	/	-	.	game_over.c*
	/	-	.	puzzle_manager.c*
	/	-	.	items_manager.c*
	/	-	.	spawner.c*
	/	-	.
	/	-	.
	/	-	- player
	/	-	.	character.c*
	/	-	.	interactions.c*
	/	-	.	mouse_look.c*
	/	-	.	attack.c*
	/	-	.
	/	-	.
	/	-	- enemies
	/	-	.	enemy_ai.c*
	/	-	.	enemy_attack.c*
	/	-	.
	/	-	.
	/	- 	- custom_nodes
	/	-	.	buttons.c*
	/	-	.	collision_events.c*
	/   -   .
	/   -   .
>
	/	assets
	/	-	- interior_design
	/	-	.	chair.gltf
	/	-	.	bed.gltf
	/	-	.	- textures
	/	-	.		chair.png
	/	-	.		bed.png
	/	-   .
	/	-	- buildings
	/	-	.	house.gltf
	/	-	.	school.gltf
	/	-	.	- textures
	/	-	.		house.png
	/	-	.		school.png
	/	-	.
	/	-	- props
	/	-	.	tree.gltf
	/	-	.	rock.gltf
	/	-	.
	/	-	- material
	/	-	.	glass_transparent.res
	/	-	.	water.res
	/	-	.	flames.res
	/	-	.
	/	-	- sound
	/	-	.	- enemies
	/	-	.	.	enemy_attack.wav
	/	-	.	.	enemy_walk.wav
	/	-	.	.	enemy_hurt.wav
	/	-	.	.	enemy_death.wav
	/	-	.
	/	-	.	- player
	/	-	.	.	player_attack.wav
	/	-	.	.	player_walk_wood.wav
	/	-	.	.	player_walk_grass.wav
	/	-	.	.	player_walk_water.wav
	/	-	.	.	player_hurt.wav
	/	-	.	.	player_death.wav
	/	-	.	.
	/	-	.	- background
	/	-	.	.	wind.wav
	/	-	.	.	rain.wav
	/	-	.	.	bird.wav
	/	-	.	.
	/	-	.	- soundtrack
	/	-	.	.	main_theme.wav
	/	-	.	.	track_name_1.wav
	/	-	.	.
	/	-	.	- FX
	/	-	.	.	explosion.wav
	/	-	.	.	water_drops.wav
	/	-	.	.	handgun.wav
	/	-	.
	/	-	- fonts
	/	-	.	NotoSansSC-Bold.otf
	/	-	.
	/	-	.
>
	/	localization
	/		English.translation
	/		Chinese.translation
	/		BrazilianPortuguese.translation
	/		Spanish.translation
	/		German.translation
	/		French.translation
	/		Italian.translation
	/		Japanese.translation
	/		Polish.translation
