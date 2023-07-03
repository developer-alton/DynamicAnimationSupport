# DAS manual
animation annotations that can make a specific scene by using hkanno64 Animation Annotation Tools (https://www.nexusmods.com/skyrimspecialedition/mods/54244)

## Annotations
### PlayEvt
	- @playEvt&{mt="", et="",nm="",ext1="",ext2="",random=100.0}

### PlaySnd
	- @playSnd&{mt="", et="",nm="",vol=0.1,expression="",eyes="",mouth="",tongue="",sos="",topic="",random=100.0}
		
### PlayBgSnd
	- @PlayBgSnd&{mt="", et="",nm="",vol=0.1,cool=1.0}

### SetPos
	- @setPos&{mt="", rotate="",offset="",side=""}

### ShowMsg
	- @ShowMsg&{msg=""}

### PlayFormSnd
	- @PlayFormSnd&{sndMod=test.esp,sndFid=0x00000,vol=0.5,topicMod=test.esp,topicFid=0x00000,expression="",eyes="",mouth="",tongue="",sos="",topic="",random=100.0}"
	
### PlayFormBgSnd
	- @PlayFormBgSnd&{mod=test.esp,fid=0x00000,vol=0.5}

	
## properties	
	mt
		# motion type
		- scene, action
	at
		# action type
		- action, notify, system
		
    	expression
		# actor can use predefined motion during scene based on MFG
    		- happy, smile, lwink(rwink), disguised, surprised, scary, angry, pain (painMild, painStrong), shamed, concentrate, embarrased, cute
    		- kiss, aroused, moan, moanMild, moanStrong, orgasm
    		- oh, ah, ee
    	eyes
		# actor can use eyes during scene based on MFG
    		- closed, up, upleft, upright, down, downleft, downright, left, right, center, reset
    	mouth
		# actor can use mouth during scene
    		- closed, tiny, small, middle, big, reset
    	tongue    	
		# actor can use tongue during scene
    		- leftRight, rightLeft, downUp, center, left, right, up, upLong, down, downLong, reset		
	topic
		- comming soon
	sos
		# for adult scene supported
		-  SOSBendDown, SOSBendUp, SOSErect, SOSFastErect, SOSSlowErect, SOSFlaccid		
	rotate
		# float | actor rotation based on radius
		- 0 ~ 360.0
	offset 
		# float | actor offset (foot unit, positive value means moving forward)
		- -1023.0 ~ 1024.0
	side  
		# float | actor side (foot unit, positive value means the left moving, negative value means the right moving)
		- -1023.0 ~ 1024.0
	
## Papyus script



## Examples

	 
