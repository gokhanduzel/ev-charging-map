# ev-charging-map

GOAL: WEB APPLICATION SHOWING EV CHARGING STATIONS ON THE MAP. IF USER CREATES AN ACCOUNT AND REGISTERS THEIR CAR MODEL, BY PROVIDING THEIR LEFTOVER CAR BATTERY, USERS ARE GOING TO BE ABLE TO SEE THE CHARGING STATIONS WITHIN THEIR BATTERY LIFE DISTANCE. IF CLICKED ON EV CHARGING STATION MARKER ON THE MAP, THE DETAILS OF THE CHARGING STATION WILL BE DISPLAYED FOR THE USER AS A POP UP.

I DECIDED TO USE "OPEN CHARGE MAP API" TO RECEIVE LOCATION AND DETAIL DATA FOR THE CHARGING STATIONS.
I DECIDED TO USE "GOOGLE MAPS API" TO CREATE THE MAP TO DISPLAY THE RETRIEVED DATA. IT IS HIGHLY CUSTOMIZABLE THEREFORE I BELIEVE I CAN CREATE A UNIQUE LOOK FOR THE MAP.

I CREATED THE BACKEND TO RECIEVE THE LOCATIONS OF THE CHARGING STATIONS. (TO MAKE THINGS SIMPLER DURING THE DEVELOPMENT PROCESS, I CURRENTLY RETRIEVE THE CHARGING STATIONS THAT ARE WITHIN 50KM RANGE OF OTTAWA.)
I CREATED THE CLUSTERED LOOK FOR THE CHARGING STATIONS SO WHEN YOU ZOOM OUT, THE MAP DOESNT LOOK LIKE A MAYHEM.

NEXT STEP: ADD INFO WINDOW
