# AndroidNotes
My personal android QA notes

**1. volatile** syntax

- `pros`:
  + declared to avoid memory consistency errors
  + ensured atomic access (default primative type are atomic access)
  + ensured that other threads will see latest change of the variable
  + more efficient than accessing variable through `synchronized`
  
- `cons`:
  + it not only sees the lastest change, but also the side effect of the code led up the change
  + need more care by developer
  
- `references`: [Atomic access] (https://docs.oracle.com/javase/tutorial/essential/concurrency/atomic.html)

**2. square image with width = screenWidth:** just provide width, height pixel same as device resolution

- xxhdpi: 1080 x 1080
- xhdpi: 720 x 1080 
- hdpi: 540 x 540
- mdpi: 360 x 360 
