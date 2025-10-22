# markov-prediction-to-bin
this markov exe file to bin
makes any file of less than 10Mb into
a bin file of 6x more the size
seems usseless but if you recompress with emma lea or paq8px or cmix
you get less 0.8% of the original size
not total recompression in recursive but its markov prediction
you may check bmx code in  blitz max
reverse engine to be done .. help wanted
markov degree 5 used and progessive acomulated blocks of nibbles

 i dont use a fixed size of block in array of nibbles to calculate cause the bigger is the range the more acurrate can be the prediction of the nibble 0 to 7
 soo i use all the filesize range from 0 to pointer actual , increzing one by  one the actual pointer every each prediction made can be more acurate thourdhtrs over the end.
 at the beggining you might not find lots of predicted right nibbles to be xored with real value and signify them as zero but
 but after predicting a compressed file over 500kb due to the more ending block you get like 1% more acurate and one per cent more zeros xored over the real value 
 nice prediction from markov degree 3 or 5 in this case
 its not impossible to recompress a simplified file of bin that is text of values of nibbles predicted from 0 to 7  values ... and a space.
 
