# Body Fat Predictor

“I don’t want a full report, just give me a summary of the results”. I have often found myself in this situation – both in college as well as my professional life. We prepare a comprehensive report and the teacher/supervisor only has time to read the summary.

Sounds familiar? Well, I decided to do something about it. Manually converting the report to a summarized version is too time taking, right? Could I lean on Natural Language Processing (NLP) techniques to help me out?

This is where the awesome concept of Text Summarization using Deep Learning really helped me out. It solves the one issue which kept bothering me before – now our model can understand the context of the entire text. It’s a dream come true for all of us who need to come up with a quick summary of a document!

## Project description
✏️ - The Machine Learning model used can predict the body fat index with 70 % accuracy, without the need for the person's density (weight under water), as this is a measurement that is difficult to obtain in real life.

🛠 - Jupyter Notebooks have been used because of their ease of use and convenience for exploratory data analysis, along with the Python language.

🚩 - The main challenge was to understand the data to be able to see that not all variables were easy to obtain in real life so there was little point in having a good model if it would be difficult to obtain those variables in a real environment.

## How to use the project
There is no executable. The notebook with the text summarizer and the attention layer needed for the project can be found in the "src" folder.

## Future lines of research
- [x] Increasing the training dataset size and build the model. The generalization capability of a deep learning model enhances with an increase in the training dataset size.
- [ ] Implementing Bi-Directional LSTM which is capable of capturing the context from both the directions and results in a better context vector.
- [ ] Using the beam search strategy for decoding the test sequence instead of using the greedy approach (argmax).
- [x] Evaluating the performance of the model based on the BLEU score.
- [ ] Implementing pointer-generator networks and coverage mechanisms.
