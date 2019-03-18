## A quick McStas demonstration

### Creating a new instrument

1. Open mcgui on your computer
2. Choose ```File ->  New Instrument``` and save under a relevant location / filename

### Insert a source

3. Position the cursor below the comment ```// insert components here (e.g. Insert -> Source -> ...)``` 
4. Use ```Insert->Source->Source_simple``` and fill in
   * a radius of 0.1 m (also default)
   * a dist of 10 m, ``` focus_xw x focus_yh ``` of 0.01 x 0.07 m
   * choose a ```lambda0 ``` of 2 Å and ``` dlambda```  of 0.02 Å
5. Press ``` Insert ``` and check that the input looks good

### Insert a sample

6. Similarly, use ```Insert->Sample->Powder_N``` to insert a sample after the source
7. Use ```"YBaCuO.lau"``` as reflections, radius of 0.005 m and yheight of 0.07 m
8. Place at 10 m from the source

### Insert a PSD

9. Use ```Insert->Monitor->PSD_monitor``` to insert a position-sensitive monitor
10.  Fill in ```"PSD.dat"``` as filename and chose ```width``` and  ```width``` both at 2 m, ```nx``` and ```ny``` both set to 401
11. Place the PSD 1m after the sample

### Run your instrument - trace mode

12. Press run on the main interface, if all is good you should now see this dialogue, where you should chose "Trace" at the top
13. A browser should now appear
14. Press run and choose Simulation again, then Start
15. Pressing Plot will give you the data from the PSD
16. Pressing ```l``` (L) for log should give you visible powder lines

