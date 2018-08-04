# Schedule

### 7/8

**3 Hours**

- Continued rewriting dFrame class
- Reworked how dFrames get layered on the timeline
 
### 7/9

**2 Hours**
 
- Created rework of Dayline
- Broad strokes of getDisplay function lined out
 
### 7/10

**4 Hours**

- Further development on Dayline class
- Note: This is important because it will help customers and employees understand how the schedule for a day is laid out
 
### 7/12

**1 Hour**

- Fixed a bug with 24-hour inputs on dTime
- Implemented addFrame function
 
### 7/14

**2.5 Hours**

- Shortened dFrame function names
- Specified a spacing value for dFrames (should match spacing for Dayline)
- Fixed a syntax bug on the toggle for dFrames
- Fixed an issue where dFrame elements' style.position's would be set twice
- dFrame pops are now display: none when hidden
- dFrame pop toggling can now be css-transitioned properly
 
### 7/18

**3.5 Hours**

- Implemented addEventListener and triggerEvent. Not all events are implemented, however
- Capitalized dFrame and dTime constructors
- Fixed a major issue with dFrame identifiers
    - Helps visual layering
- todo: implement this fix on Dayline
- Merged all classes into one file
- Set dTime and dFrame as "dependent classes" or "subclasses" of Dayline (Accessed via Dayline.DFrame and Dayline.DTime)
- Fixed a bug with popups displaying initially
- Fixed a bug where dTimes with no constructor input would return an getTime of "0:00"
- Fixed a bug where dTimes could not be constructed from dTimes
- Added updateForm to streamline data updating

### 7/20

**2 Hours**

- todo: additional input scrubbing for dTime
- Began fixing time inputs on form. Added getDefault method to dTime
- getDefault method still requires more fixes to work.

### 7/21

**4 Hours**

- Complete revamp of main form. Cut all coordination with auto shop for now.
- todo: route and time estimation

### 7/31

**3 Hours**

- Created email sending at end of form
- Formatted email

### 8/4

**2 Hours**

- Error message if reached route estimation cap
- Backup handling for that scenario