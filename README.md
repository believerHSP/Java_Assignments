# Java_Assignments

Test Cases: Piano_Sound Using_Java

(i)  Pressing a Valid Key

Summary: 

To Test that: 
C note is being played when c key is pressed

[Description]

Given On running the Piano class.
When I simulate pressing the 'C' key
Then the C note should be played
And there should be no errors

Desired Result: Passed
[Actual Result: ]


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
(ii) Pressing an Invalid Key

Summary:

To Test that: 
no sound played when a key that is not mapped to a piano note is being pressed

[Description] 

Given On running the Piano class.
When I simulate pressing a key that is not mapped to a piano note
Then there should be no sound played
And there should be no errors

Desired Result: Passed
[Actual Result: ]

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
(iii)  Simulating Multiple Notes Sequentially

Summary:

To Test that: 
Two notes should be played on being pressed consecutively. 

[Description] 

Given On running the Piano class.
When I simulate pressing the 'C' key and then the 'D' key
Then the C note should be played followed by the D note
And there should be no errors

Desired Result: Passed

[Actual Result: ]


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
(iv)  Simulate Holding Down a Key

Summary:

To Test that: 
Sound should be played continuously until lifting the finger up.

[Description] 

Given On running the Piano class.
When I simulate holding down a key for a duration
Then the corresponding note should be continuously played
And there should be no errors


Desired Result: Passed

[Actual Result: ]

+++++++++++++++++++++++++++++++++++++=+++++++++++++++++++
(v) Simulate Stopping a Note

Summary:

To Test that: 
The sound should be stopped on releasing a key.

[Description] 

Given On running the Piano class.
When I simulate pressing and releasing a key
Then the corresponding note should stop playing
And there should be no errors

Desired Result: Passed

[Actual Result: ]







