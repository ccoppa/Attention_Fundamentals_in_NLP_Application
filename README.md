# Attention Mechanism Fundamentals
## Introduction
> "One important property of human perception is that one does not tend to process a whole scene in its entirety at once. Instead humans focus attention selectivly on parts of the visual space to acquire information when and where it is needed, and combine information from different fixations over time to build up an internal representation of the scene..." - Recurrent Models of Visual Attention, 2014

Attention mimics the way that our brain processes content by utilizing what is called "attention context vector", which focus its attention on the appropriate place in the input sequence. In a synopsis, attention context vector explores the relationship among sequences' hidden state representations, summarizes the relationship and then decodes the relationship by selectively focus on different parts of the content and sequentially collects and process information over time. 

Attention helps powers up some of the best performing models spanning both natural language processing and computer vision. These models include: neural machine translation, image captioning, speech recognition, text summarization, as well as others. In this notebook, we look at how attention is implemented by going through its derivations.
