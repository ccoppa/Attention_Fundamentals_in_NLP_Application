# Attention Mechanism Fundamentals
## Introduction
> "One important property of human perception is that one does not tend to process a whole scene in its entirety at once. Instead humans focus attention selectivly on parts of the visual space to acquire information when and where it is needed, and combine information from different fixations over time to build up an internal representation of the scene..." - Recurrent Models of Visual Attention, 2014

Attention tries to mimic the way that our brain processes content by utilizing what is called "attention context vector", which weights its attention on the appropriate place in the input sequence. In a synopsis, attention explores the relationship among the input sequences' hidden state representations, weights the relationship into attention context and then RNN decodes the attention context by selectively focus on different parts of the content and sequentially collects and process information at each iteration in the Decoder output sequence. 

Attention helps powers up some of the best performing models spanning both natural language processing and computer vision. These models include: neural machine translation, image captioning, speech recognition, text summarization, as well as others. In this notebook, we look at how attention is implemented by going through its derivations.
