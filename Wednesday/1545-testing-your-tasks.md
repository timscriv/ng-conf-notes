# Julie Ralph - Testing your Tasks

- zone.js
    - Heavily used by Angular 2
- Zones are a patch over all the event loop inners. 
- Zones that you fork are children of the creator
- We can have multiple zones 
- More Zone examples
    - github.com/angular/zone *something something*
- Angular 2 Change Detection
    - When it is out of the zone change detection is not fired 
- Testing
    - End to end
        - protractor tests can wait for pages to load before executing (no race condition)
    - Unit tests
        - async and fakeAsync will wait for tests to finish
        - this would be like returning your promises correctly but can promises can be easily messed up
- fakeAsync
    - Allows precise control over timing
    - tick() simulates changing time 
- further reading
    - https://github.com/juliemr/ngconf-2016-zones
