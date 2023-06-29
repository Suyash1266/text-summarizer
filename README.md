# Text Summarizer
A simple python notebook which utilises the power of transformers to generate a summary of the input text

## Summarization
The summarization feature uses the pre-trained model from Google, Pegasus, specifically pegasus-large. Other variants can be used to run the code on low end machines, namely the pegasus-cnn_dailymail and pegasus-newsroom. This can be modified by changing the model name in the `generate_summary()` function.
```python
model_name = 'google/pegasus-large'
```

Other paramters can also be fine-tuned to enhance the performance of the summarization model to match your specific needs.

## User Interface
The notebook also utilizes the IPython library to create a simple user facing interface where user can input the text they want to summarize and get the summary of the text.

## Screenshots
![image](https://github.com/Suyash1266/text-summarizer/assets/35092213/568456e1-7857-4e60-982d-9e54822cd493)

![image](https://github.com/Suyash1266/text-summarizer/assets/35092213/9ec3a79d-8211-442c-95ed-f307512c90db)
