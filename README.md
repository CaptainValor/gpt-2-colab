# DhammaBergGPT2 #

Adaptation of https://github.com/ak9250/gpt-2-colab

Allows re-training of OpenAI's GPT-2 117M Model in Google Colab.

Includes code for building a single huge English training text file based on Project Gutenberg (books) or Access to Insight (Dharma texts). ATI seems to overfit quite rapidly since it's only 6 MB, but a 99 MB subset of Gutenberg came out quite convincing after only 4 hours of training. Your mileage may vary.

## Samples from Gutenberg99 ##

Model prompt >>> I love you.       
======================================== SAMPLE 2 ========================================
 Do you love me?"

She had just looked at him and smiled again.

"Yes," she said. "I love you."

She was in tears.

"But I will not keep you long," he said.

- - -

Model prompt >>> The rain in Spain falls mainly in the plain. She sells seashells by the seashore. 
======================================== SAMPLE 1 ========================================
 The
dwarf's eye, the fern, and the red-bearded beard have all been swept into
the sunshine.  These were the days when the rich and the poor were
t
======================================== SAMPLE 2 ========================================

In the mountains there are many glaciers.  We find them in the valleys of
the Seychelles.  They are so thin that even the best of the snow is
overgrown with them
======================================== SAMPLE 3 ========================================

The city of St. Mark, in the north-west, and the city of Pampeluna are,
in a general sense, the same, with a great number of inhabitants,
mostly
