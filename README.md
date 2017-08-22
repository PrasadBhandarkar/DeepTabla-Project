# DeepTabla Project

Deep Tabla is AI powered tabla accompaniment. It is based on recurrent neural network.
This implementation is based on Tensorflow.

This project is create to prove that Artificial Neural Networks can produce improvisational music when trained sufficiently.

## Background
# Basics of Tabla
Tabla is a north Indian percussion instrument. It comprises of two drums played together.

Tabla is a unique percussion instrument and can produce extremely rich and advanced percussion improvisations. This is so because like human languages, Tabla has its own language. Various sounds on each drum have their own naming convention like alphabets in English. A combination of alphabets form words, a combination of words form sentences and sentences spoken with accent form compositions.

An example of a 16 beat "sentence" in tabla could be - "Dha Dhin Dhin Dha Dha Dhin Dhin Dha Dha Tin Tin Ta Ta Dhin Dhin Dha". The word "Dha" itself comprises of two alphabets - "Ta" played on left (smaller) drum and "Ge" played on right (bigger) drum.

More information on tabla can be found here.
https://www.youtube.com/watch?v=nJFO9UxQW8o https://www.youtube.com/watch?v=fbIm5y0pxr8

# Teentaal
Teentaal is a very common rhythmic cycle of 16 beats. It is characterised by the following -

The first beat is called "sam" (pronounced as "sum"). It is the emphasis beat and a good tabla player would show it distinctly during the course of improvisation.

The cycle of 16 beats is divided into four segments of four beats. The third of the four segments - i.e. beats 9, 10, 11, 12 - is called "khali" and is presented in a peculier way. Even in the course of improvisation, a good tabla plays this segment in a distinct way.

Teentaal has its basic structure - "Dha Dhin Dhin Dha Dha Dhin Dhin Dha Dha Tin Tin Ta Ta Dhin Dhin Dha". However, in a real concert a good tabla accompanist would not play it this plainly. A good tabla player would improvise this cycle, taking influences from his own training and from the main artist. During the course of improvisation, the tabla player would create percussion freely while maintaining the rules indicated above. An example of this interaction can be seen here.
https://www.youtube.com/watch?v=LZ8BJfU-7t8

# AI Tabla - What is Success
Here are a few things AI tabla should be able to do to claim success -

1. Maintain the cyclicity of beats in the rhythmic cycle. If playing Teentaal which is of 16 beats, the AI should predictably play 16 beats with highest certainty all the time. It should never play 15 or 17 or 13 or any other number of beats in a cycle.
2. It should show emphasis on the first beat ("sam")
3. It should show the khali beats (3rd segment of 4 beats as explained above) appropriately.
4. It should be as original as possible. Much of its improvisation should be original. i.e. it should not simply copy cycles from training data.

For the purpose of demo below, the training dataset is comprised of millions of cycles of 16 beats. It has the first beat in all upper case letters to denote its distinction. It also has the improvised version of 3rd segment throughout.
