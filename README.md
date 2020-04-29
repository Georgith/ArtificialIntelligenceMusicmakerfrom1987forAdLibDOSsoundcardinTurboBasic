# ArtificialIntelligenceMusicmakerfrom1987forAdLibDOSsoundcardinTurboBasic
Artificial Intelligence Musicmaker from 1987 for AdLib DOS soundcard in Turbo Basic.

This is a later version of an old DOS Borland TurboBasic Artificial Intelligence Music making program I first wrote in about 1988 or so for historical reference Just for those who never saw the Old Borland TurboBasic which was really the first widepsread compiled basic available for the PC in 1987-88. 

This used the AdLib soundcard which was the first soundcard of the IBM PC and I talked on the of reps into lettingme get an early example to program for.
https://en.wikipedia.org/wiki/Ad_Lib,_Inc.

I wrote this using Borland TurboBasic which great because it was compiled Basic which ran fast and it provided you with a standalone program you could run without anyrun times like the common versions of Basic needed back then.

The program itself used a pattern technique. I choose random patterns of notes and assebled them into random patterns of music and repeated those with slight variations to produce songs. I didnt knowmuch about mousic at the time so frankly the result wasnt good becuase I was having it pick ranadom note frequencies etc without regard fro chords etc.

However the AdLib board was breakthrough then because you could produce multiple simultaneous voices (notes) which the PC couldnt do then. And it let you manipulation the sound envelope of each note directly without basic frequency,attack, delay, decay and other parameters. 

MIDI had just been invented. The board could be addresse dat the high level MIDI or at the hardware level as I discussed. You can see some of both in the code.

As I recall this also produced some somewhat pleasing graphics on the screen in the form of shapes like colorful arcs etc and the music played.

At this time I was fascinated with the emerging field of artificial intelligence and had created a back propagation nueral network on a free shareware spreadsheet called ASEASYAS and was also jumping into genetic r evolutionary algorithms. I had intened to turn these music patterns into a full fledged genetic algorithm as I fully developed this and as you can tell many of the musical note patterns are similiar to the "genes" sequnces that are modified in a typical evolutary algorithm program. I forget how far I got in the effort. I beleive the goal was to have thePC make the music and then have the user keep giving it positive of negative feedback via the keyboard until the program evolved each song into something that was good.


note: the "neatend" at the top is the result of another program I wrote which would neaten up the turbobasic code I wrote inserting proper indents etc and even followed nested lopps etc. I'll upload that later because it could the beginning basis for an interpreter or compiler. When I ran the program called "neatenup.bas on a program file it output that file to another file called "neatened.bas" and that had the date and time it was neatend at the top. Hence this.

to actually run this you would need the turbobasic runtime which was called tb.exe I beleive and you would do a command line instruction like  tb.exe planets.bas or whatever the program name was. tb.exe also had a IDE believe it or not that was pretty could with error tracing and other things and even allowed you to program inline assembly code. all in DOS alphanumeric windows. If you could find the runtime this would probably run in a dosbox.

apparently there is a german version of the runtime available at internet archive https://archive.org/details/BorlandTurboBasic1.0German

also there is a book about turbobasic on archive . dot org too althogh it isnt the original ownershandback and reference that came with the program. It does however explain many fo the sophisticated features of turbobasic at the time like recursiona nd case and other things https://archive.org/details/UsingTurboBasic/mode/2up

Turbobasic was extraordinary at the time becuase it was cheap and unlike microsoft basic or qbasic etc it actually compiled and gave you a standalone program you could give to your friends who could run it on their own dos ibm computer without and other libraries or programs needed and hence no licensign fee from anyone like Microsoft. This meant you could produce REAL PROGRAMS that you could sell and deploy! At that time that was pretty execptional for a low cost consumer development environment and program. (I think it was maybe $75 to $95 back then). I am pretty sure the compiler even let you compile for fastest execution or smallest size and let you choose whether or not to make it require an 8087 chip which was a "math coprocessor" which considerably sped up most math calculations! Keep in mind this was all before sound chips or graphics chips existed or were really even a dream in someones head for a consumer PC...except for Amigas.

