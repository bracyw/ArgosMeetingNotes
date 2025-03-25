# Meeting Outline ~ 3-25-2025

## Base Design Adjustments
1. Routing standardization - current idea: 
	1. function based selections, wrap with '/' prepend for use around application
	2. Labels and names also abstract? - maybe not
2. data-type.enum .... into topic-utils
	1. again function based for dynamic topics: same setup as api urls
3. Handling of definitions for specific inputs when using something like dynamic urls                  ---- goes into BMS Debug 

## BMS Debug - Design Decision's  
1. basically what do we do with the definitions for possible segments, cells, etc. enums are a little annoying. Examples of this in finishline? pull up how I'm doing it right now.
2. Sharing data between heat map and extra info comp: Service makes things complicated if they are persisted across pages... 
	1. do we want one for Cells (probably... one for what the heat map is on?, or generic?),
	2. do we want one for display type? (maybe... or just have it be what the heat map is currently on, and then our companion comp can infer from that)
3. Issues with component not reloading when simple signal input is changed, way around this to begin with?.... pull up subscribe / unsubscribe solution currently
4. Jack 

## Open Tickets Checkin 
1. Peyton - fault page + fault graph 📈 🎉🎉 - change naming with serde for types?
2. Emir - Seg at a glance - basic set up done... waiting on me for changes to handling different segment inputs
3. Karim - pie chart - just make those few changes and it's merged
4. Justin - abstract Angular form / run edit - hardest part finished, 1) main thing: hook up backend, 2) second style

## Jack Questions
1. What can we put in too companion component?
2. Yell at harrison to fix mock? lol 
3. Agree with Reids graph screen ticket.


