<h2>GFM Poland submod by Psikoota</h2>
<h3>Contents:</h3>


*/common/countries/Poland-Lithuania.txt*
- changed map colour to be darker/paler like Poland, with PLC's shade of pink


*/gfx/pictures/decisions/*  
- removed loss of cores for PLC and PLR decisions


*/events/*
- November Uprising event chain if Poland is winning by 4% or greater
  - Republic path: Poland gets prestige but Prussia and Austria will declare war
  - Regency path: plurality boost, later event for Prince Radziwiłł to become king
  - Monarchy path: Prince Czartoryski becomes king (lose plurality but gain "Great Statesman" modifier)
  - Regency and Monarchy paths get an event to negotiate peace with Russia if they are still winning
- "Returning Exiles" event gives research and education efficiency boost
- "Wedding to the Sea" event gives permanent "Naval School" modifier (+5% naval tech boost)
- "Grand Theatre of Warsaw" event gives "Opera House" modifier (immigration boost)
- "Napoleon's Example" event can trigger if Poland is at peace and France is not allied with Germany, Prussia, or Austria (can repeat, but less likely); grants alliance with France


*/gfx/flags/*
- PLC/PLC_republic: matching reds
- PLC_communist: red banner (PRL shade) with white PPS splinter group logo WRN
  - PLR_communist matching
- PLC_fascist: white banner with crimson lightning logo from NSPR, a 1933 Polish national-socialist party
  - PLR_fascist matching
- PLC_monarchy: different shape coat of arms, darker red
- PLR/PLR_republic: matching shades of red, darker blue
- PLR_monarchy: matching shades of red, darker blue, with crown
- POL_monarchy: white-red bicolour with Polish eagle and crown


*/gfx/pictures/events/*
- event pictures for new events


*/localisation/*
- localisation for new events
- PLR names shortened to just "The Commonwealth" so they fit UI and the map
- PLC and PLR adjectives both changed to "Polish" to reflect how people wrote about Poland-Lithuania


<h3>Planned content:</h3>

- event: Support the Greater Polish Uprising of 1848
  - Poland can annex Greater Poland, though Prussia will immediately declare war
  - Note to self: maybe make this a 1 on 1 war? So Prussia can't call 5 million allies?
- event: Support the Krakow Uprising
  - Poland can annex Krakow, though Austria will immediately declare war
  - Note to self: maybe make this a 1 on 1 war, as noted above
- event: Jewish Community Threatened
  - can happen if ashkenazi not accepted AND any province >8% ashkenazi
  - Nice option (adds consciousness and desire for culture law change)
  - Mean option (adds militancy, decreases ashkenazi population by 1%, adds modifier tax income -25% in that province)
- event: Organic Work? Book Clubs? idk (basically spontaneous liberty associations or land reform pressure)
  - MTTH 2 years; debt law is Serfdom/Peonage
  - In a single region:
    - education eff +5%
    - add con, +desire for abolish serfdom
  - OR Tank education eff, add militancy
- decision: Land Reform
  - Debt law not Serfdom/Peonage (serfdom must be abolished first); Economic policy not Laissez-Faire (ie oppose intervention)
  - Add "national chaos" modifier; Add mil for upper classes; Add "land reform" modifier (idk pop boost?)
