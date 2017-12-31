# LangProbParser

The csv file is a copy of a database detailing how lanugages use length, pitch, and intensity to show stress. It includes what families each language is in, as well as which of those three correlates each uses and on what syllables stress will fall.

The python runs a monte carlo to see if the various languages inside of a family act like family members. They should be more likely than random to use a correlate if their family members use it, and vice-versa.

So it shuffles the families together to make 'fake' families, and sees whether the real dataset has significantly more similar languages paired together.

The real dataset does appear to show language families act like they are related.

This information was used to help inform the veracity of the database for "Vowel-length contrasts and phonetic cues to stress: an investigation of their relation"

https://www.cambridge.org/core/journals/phonology/article/vowellength-contrasts-and-phonetic-cues-to-stress-an-investigation-of-their-relation/2839919AEA482697DBDAA513EE086D04
