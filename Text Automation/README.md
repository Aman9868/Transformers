
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


