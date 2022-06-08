DayZ 1.18 Livonia Standard & Helicoter Trader For Use With Dr Jones Trader & RFFS Heliz

THESE ARE THE TEXT SNIPPETS FOR THOSE THAT WOULD LIKE TO MODIFY THEIR OWN TRADER CONFIG FILES,
PROBABLY BEACAUSE YOU HAVE OTHER MODDED ITEMS ALREADY INCLUDED, OR DAYZ HAS PROGRESSED PAST 1.18.

IF YOU'RE RUNNING A VANILLA 1.18 LIVONIA SERVER JUST UPLOAD THE SUPPLIED TraderObjects.txt and TraderConfig.txt and TraderVehicleParts.txt files to the
Trader Config folder inside your Server Config / Settings / Profile folder.

MANY THANKS TO DR JONES & RED FALCON

Trader is at 8728.16 / 8076.48, South East of Zapidlisko.

ADD THIS TO THE FIRST HALF OF TRADEROBJECTS.TXT AFTER THE (Tradermarker> 5 Entry:

<TraderMarker> 6
<TraderMarkerPosition> 8718.33984375,                289.1860046386719,                8086.18994140625
<TraderMarkerSafezone> 20
<VehicleSpawn>  8758.009765625,                285.4729919433594,                8093.16015625
<VehicleSpawnOri> 11.74329948425293,                -2.2143497467041017,                -2.522050142288208

ADD THIS TO THE SECOND HALF OF TRADEROBJECTS.TXT AFTER THE <Object> SurvivorM_Peter	ENTRY:

<Object> 			SurvivorM_Boris					// heliz
<ObjectPosition>	  8718.33984375,                289.1860046386719,                8086.18994140625
<ObjectOrientation>	  125.69999694824219,                0.0,                0.0
<ObjectAttachment>	RFFSHeli_PilotHelmet
<ObjectAttachment>	RFFSHeli_PilotGloves
<ObjectAttachment>	RFFSHeli_PilotShirt
<ObjectAttachment>	RFFSHeli_PilotPants
<ObjectAttachment>	RFFSHeli_PilotVest
<ObjectAttachment>	MilitaryBoots_Black

<Object>			Land_RoadCone
<ObjectPosition>	8759.3583984375,                285.24163818359377,                8099.6796875
<ObjectOrientation>	  0.0,                0.0,                0.0
 
<Object>			Land_RoadCone
<ObjectPosition>	 8764.220703125,                286.00311279296877,                8088.80615234375
<ObjectOrientation>	  0,                0.0,                15.999994277954102

<Object>			Land_RoadCone
<ObjectPosition>	 8750.7734375,                285.5110168457031,                8091.478515625
<ObjectOrientation>	 0,                0,                0

<Object>			Land_RoadCone
<ObjectPosition>	  8755.7373046875,                286.0806579589844,                8081.2177734375
<ObjectOrientation>	  0,                0.0,                0.0

ADD THESE TO TraderVehicleParts.txt BELOW THE LAST M3S ENTRY:

<VehicleParts>RFFSHeli_Bo105m 
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7
        HeadlightH7

<VehicleParts>RFFSHeli_Bo105m_blackcamo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird 
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird_Camo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird_Desert
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_Ka26
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness 
        HeadlightH7   

<VehicleParts>RFFSHeli_Bell429
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Bell429_Police
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Bell429_Medic
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7

<VehicleParts>RFFSHeli_Mi2
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 
		
<VehicleParts>RFFSHeli_Mi2_Military
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Mi2_Hornet
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 	

<VehicleParts>RFFSHeli_Apache
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7  	

<VehicleParts>RFFSHeli_Apache_Winter
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 	

<VehicleParts>RFFSHeli_Apache_Desert
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22_Red
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22_Black
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_Blackhawk
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7	

<VehicleParts>RFFSHeli_Blackhawk_Cargo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7

<VehicleParts>RFFSHeli_Blackhawk_Woodland
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7

<VehicleParts>RFFSHeli_CH53e
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7
		

ADD THESE TO TraderConfig.txt, near the bottom, after the VehicleKeyLost entry:

<Trader> Heli Trader	
	 <Category> Helicopters
        RFFSHeli_Bo105m,            VNK,    50000,        -1
        RFFSHeli_Bo105m_blackcamo,            VNK,    50000,        -1
        RFFSHeli_LittleBird,        VNK,    50000,        -1
        RFFSHeli_LittleBird_Camo,    VNK,    50000,        -1
        RFFSHeli_LittleBird_Desert,    VNK,    50000,        -1
        RFFSHeli_Ka26,                VNK,    50000,        -1
        RFFSHeli_Bell429,                VNK,    50000,        -1
        RFFSHeli_Bell429_Police,                VNK,    50000,        -1
        RFFSHeli_Bell429_Medic,                VNK,    50000,        -1
        RFFSHeli_Mi2,                VNK,    50000,        -1
        RFFSHeli_Mi2_Military,                VNK,    50000,        -1
        RFFSHeli_Mi2_Hornet,                VNK,    50000,        -1
        RFFSHeli_Apache,                VNK,    50000,        -1
        RFFSHeli_Apache_Winter,                VNK,    50000,        -1
        RFFSHeli_Apache_Desert,                VNK,    50000,        -1
        RFFSHeli_R22,                VNK,    50000,        -1
        RFFSHeli_R22_Red,                VNK,    50000,        -1
        RFFSHeli_R22_Black,                VNK,    50000,        -1
		RFFSHeli_Blackhawk,                VVNK,    50000,        -1
        RFFSHeli_Blackhawk_Cargo,                VNK,    50000,        -1
        RFFSHeli_Blackhawk_Woodland,               VNK,    50000,        -1
        RFFSHeli_CH53e,                VNK,    50000,        -1


    <Category> Helicopter Parts
        RFFSHeli_hydraulic_fluid,    *,    200,        -1
        RFFSHeli_hydraulic_hoses,    *,    200,        -1
        RFFSHeli_wiring_harness,    *,    200,        -1
        RFFSHeli_igniter_plug,        *,    200,        -1
        RFFSHeli_aviation_battery,    *,    200,        -1
        RFFSHeli_aviation_toolbox,    *,    200,        -1
		RFFSHeli_flight_case,		*,		200,			-1
		RFFSHeli_flight_case_red,		*,		200,			-1
		RFFSHeli_flight_case_blue,		*,		200,			-1
		RFFSHeli_batterycharger,		*,		200,			-1
		
	<Category> Helicopter Gear
		RFFSHeli_PilotHelmet,		*,		200,			-1
		RFFSHeli_PilotGloves,		*,		50,			-1
		RFFSHeli_PilotShirt,		*,		100,			-1
		RFFSHeli_PilotPants,		*,		100,			-1
		RFFSHeli_PilotVest,		*,		50,			-1