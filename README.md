# Re-modernising-Gypsy-Woman

General Info:
This project is a creative re-imagining of Crystal Waters’ 1991 classic “Gypsy Woman (She’s Homeless)”, recreated entirely through code using TunePad, a Python-based musical composition platform. The aim was to translate the rhythmic, soulful essence of early ’90s deep house into a modern coded composition — combining algorithmic logic, digital sound synthesis, and artistic creativity. This project explores how music and code can merge to form a new kind of digital musicianship, where loops, functions, and lists become instruments for storytelling and emotion

Technologies Used:
Python (TunePad environment) – Core programming language for composition and playback
TunePad Libraries – For generating and sequencing musical notes (playNote, rest, beats)
Digital Audio Sequencing – For layering instruments (bass, organ, guitar, drums)
Git & GitHub – For version control and documentation

Features:
Algorithmic Composition: Each instrument (bass, guitar, organ, drums) is generated using Python loops and conditionals to emulate the structure of a 1990s house track.
Multi-Instrument Layering: Code produces layered musical parts that align rhythmically and harmonically.
Custom Sound Mapping: Instruments are defined by MIDI note values to build melodic and harmonic sequences.
Syncopated Rhythms: Incorporates off-beat rests and varying beats lengths to replicate the groove of deep house.
Expandable Structure: Sections can easily be extended or remixed by adjusting loops and note progressions

Setup:
A TunePad account, internet browser with audio enabled, (Optional) a local Python 3 environment with libraries for sound generation if exported outside TunePad
  If exported to Python, dependencies should be listed in a requirements.txt file.

Usage:
To use or remix this project:
Open in TunePad and upload or paste the project code into a new TunePad project.
Run the code and press “Play” to hear the full track.
Modify instruments; Try changing the note values or beats to create a remix:

  # Example: Modify bass groove
  playNote([C, Eb], beats = 4)
  rest(1)
  playNote([Ab, C], beats = 3)


Experiment:
Adjust chord voicings in the organ part.
Add syncopation in the drum pattern.
Extend loops for a longer or more dynamic arrangement.

Project Status:
Complete - based on proposal at the beginning of the semester. I never intended to re-imagine the entrety of the song, in order for it to be further re-imagined by audiences.

Room for Improvement:
Add tempo and filter modulation for smoother transitions.
Implement live input or MIDI controller support for real-time performance.
Introduce visualisations that respond to the beat using Python graphics libraries.
Fine-tune timing for greater rhythmic accuracy

Acknowledgements:
This project was inspired by:
“Gypsy Woman (She’s Homeless)” by Crystal Waters (1991) – a defining track of early house music
TunePad, for enabling musical creativity through Python
University of Technology Sydney (UTS), for the artistic coding brief that encouraged merging creativity and computation
The broader digital arts and creative coding community, whose work continues to blur the line between art and technology
Many thanks to Crystal Waters for creating a timeless house track that is still relevant today, breaking the boundaries of house music and code in a modern society.
