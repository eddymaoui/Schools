# Introduction exercise to Sources and Monitors

The purpose of this exercise is simply to get familiar with the concepts of Source and Monitors in McStas.
We will insert a source and two monitors and then modify these to examine some internal properties.

## Initial works.
1. Start a new instrument simulation and insert a circular source ( Source_simple ) in the trace section, to emit neutrons with wavelengths in the interval
lamdba=[1 8] AA. Focus the sampling at a rectangle downstream.
2. Insert a PSD_monitor and a L_monitor at the same position as the focusing rectangle. Make sure they capture the full radiation of the source. Do you see what you expected? It should look something like this ![First Results mcplot](images/2_Sources_and_Monitors/2_Sources_and_Monitors_1st.png)
3. Move the PSD_monitor up close to the sourfce. What happens to the spatial distribution?
4. Add the parmeter "gauss=1" to the source and see what happens.
5. Now change the source to be of the type Source_div. This also implies replacing the "focus_xw", "focus_yh", and "dist" parameter with the angular focusing parameters: "focus_ah" and "focus_aw".
6. Try to switch "gauss" off, to see what happens.

7. Can you add a divergence monitor: "Divergence_monitor"? 
##   

