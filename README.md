# touchDesignerTimecodeUtility
A Touch  Designer patch that triggers queues with timecode inputs


The toe file includes a demo of the TOX working. with a demo list within the TOX and demo lists being serched.

the Tox on it's own needs timecode Audio to work correctly

Includes triggering of switches based on a table input.
op.TC.SwitchCheck(op("switchIndex1"), me.path) # switchindex1 is the list of names you are checking are in the cue column of your list of cues. 
If the cue in the list matches the cue name in the cue column, the switch updates to that row in the list.
me.path just gives python storage a unique name to store the current que.

ocs string writing for Resolume clip triggering - we write a list of clip / layers that need triggering if they have a clip and layer number assigned in the cue list.
