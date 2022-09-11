# Data Science Portfolio
Each project represented here that is marked with "Additional Participants" was a group project with others, the readme in each subfolder will contain a directory of which files I contributed code to, as well as a detailed description of how to run the code and what its purpose was.

# [Cyrano: Improving Couples' Communication Through Empathetic Dialogue](https://github.com/jaredcdec/Data_Science_Example_Projects-Cyrano)
Additional Participants: Joe Mirza, Ziwei Zhao

For the final capstone of my Master's in Data Science, a team of myself and two others built an NLP tool that was designed to improve the empathy in the words couples used when messaging each other. 

- Takes as input the partner's original message as context, the user's message (or reply to earlier message) is analyzed and evaluated for empathy. I fempathy is too low, message is rewritten, two methods for rewriting were built. 

- Uses empathy ratings for tokens from a previous study, tool was built on top of a chatbot built for huggingface.

- Keywords: Python script

# [Detecting Toxic Speech in Korean and Hinglish](https://github.com/drkulkarni236/w266_finalproject)
Additional Participants: Devashish Kulkarni, Mili Gera

This was the final project of my DATASCI W266 class, otherwise known as Natural Language Processing Using Deep Learning, which I took during my master's in Information and Data Science. The purpose of this project was to compare the relative performance of two methodologies, mBERT and LaBSE, for text classification tasks in languages that are very similar to English (code-mixed Hindi and English) and languages very different from English (Korean). The original hypothesis was that LaBSE, which is a language-agnostic framework, would handle languages with significant grammatical and cultural differences from Western European languages better than mBERT or more traditional transformer-based models which were largely built on data from English or other similar languages. This did prove to be correct in our use case but only to a very marginal extent. 

The final paper summarizing our methodology and findings can be found [here.](https://github.com/drkulkarni236/w266_finalproject/blob/main/Hate%20Speech%20Detection%20in%20Hinglish%20and%20Korean%20Media.pdf)

- Uses two datasets of toxic speech, one in Korean and one in "Hinglish" (code-mixed Hindi and English). 

- Compares performance on toxic speech detection in languages with significant cultural and linguistic differences from English and languages similar to English using traiditional mBERT models and language-agnostic BERT frameworks.

- Results show that relative performance gains exist but are very minor.

- Also experiments with performance with relative performance of transfer learning based on Engflish toxic speech when applied to these two languages, as English toxic speech data is far mroe widely available.

- Keywrods: python script, tensorflow, NLP
