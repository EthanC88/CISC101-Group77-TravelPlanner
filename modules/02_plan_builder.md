> Change log (2025-11-23)
> - Updated
Define required inputs and assumptions:
  - Inputs: lodging location, trip dates, budget target, preferences, exclusions. 
  - Assumptions: default walking radius, max daily transit time.
Make selection rules explicit
    Morning: within X minutes from lodging; target low-crowd activities.
    Midday: cluster within Y minutes of the morning activity; include lunch window.
    Afternoon: “different theme” = not same type/subtheme as earlier activities; prefer indoor if poor weather.
    Evening: select restaurant or event within Z minutes of afternoon spot or near lodging.
    
### **Module 2 — Plan Builder (Options → Days)**

Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:  
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event
