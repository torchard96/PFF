How to open
1.Download Unity version 2018.1.1 (64bit)
2.In unity select folder PFF 0.02.000
3.???
4.Profit


How to edit game
For editing the camera, select the Main Camera in the hierarchy
then you can edit stuff in the inspector under Camera Controller

SensivityX: left right sensivity
SensivityY: up down sensivity (note negivite number will invert camera movment)


For editing the Player, select Player in the hierarchy
then you can edit stuff in the inspector under Player Controller

	Jump_force: force applied when player jumps
	DoublejumpfTime: how much time the player stays in the air after a double jump
	Gravity_acc: gravitional acceleration
	GroundCheckDistance: distance used in checking isGrounded (deprecated)
	PlayerMovmentForce: force applied by pressing movment keys
	CoffOfDrag: drag force multiplier (note PlayerMovmentForce and CoffOfDrag ratio very strongly determines how game feels)
	Drag_in_air: weither drag is applied while the player is in the air (note turning this off means the players could get some serious speed if they just keep jumping)
	Ghost_time: how long to wait after the player falls off a ledge before they can't jump (used to fight latency both in screen and in input)
	Jump Angle Limit: any slope higher than this the player can't jump on
	Walk Angle Limit: any slope hight than this the player can't walk up
