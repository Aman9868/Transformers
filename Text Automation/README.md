
# Text Automation

Solve all Daily life Text related problem like:

    1. Text Classification.
    2. Text Summarizer.
    3. Named Entity Recognition.
    4. Sentiment Analysis.
    5. Text Translation.
    6. Question & Answering.
    7. Text Generation.
## Deployment

To deploy this project run

```bash
  streamlit run app.py --server.maxUploadSize=1028 & npx localtunnel --port 8501
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`!pip install transformer`

`! pip instll streamlit`


## Usage/Examples

```javascript
from transformers import pipeline
classifier=pipeline("sentiment-analysis")
classifier("I've been waiting for  Hugging Face course my whole life.)

```


## Screenshots
![image](https://user-images.githubusercontent.com/60923869/151026671-aa3d7389-deab-479a-be92-ab8adbacf380.png)

## Demo
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/60923869/151031668-ad6f1a0d-30a1-4add-878a-ef1e2303bdbb.gif)

