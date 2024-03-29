# Chinese-English Machine Translation using a Weighted Transformer
This is a project using the UM Corpus dataset, and trained with a Weighted Transformer. It includes all the data processing and engineering as well.

Feel free to try running this notebook with different hyper-parameters and try to improve it. It also includes an implementation of a standard Transformer,
so you can try that out as well

You can download the dataset here http://nlp2ct.cis.umac.mo/um-corpus/, and import it into Drive and connect Colab to your Drive in order to use the dataset. From there you can easily import this notebook into Colab and run it.

# Details
This project is trained only on the Spoken section of the UM corpus dataset which contains around 200,000 examples, since training on the entire 2,000,000 examples
would take too long. I trained with a small Weighted Transformer model to train quickly, but you can try using a bigger model or more data (it is very easy to change the hyper-parameters) to increase the performance. The Spoken and Microblog sections seem to have the best data for general language translation.

Here are the links to the papers I implemented in this project.

Transformer paper: https://arxiv.org/abs/1706.03762

Weighted Transformer paper: https://arxiv.org/abs/1711.02132

# Contact
You can contact me at neelrayani@gmail.com if you have any suggestions or questions.
