---
stoplight-id: hdazb71rveo7w
---

# Overview

[**Sentiment analysis**](https://en.wikipedia.org/wiki/Sentiment_analysis) (also known as opinion mining or emotion AI) refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to identify systematically, extract, quantify and study affective states and subjective information. Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine.

This API will detect the sentiment of a string (e.g. 'This is great') and reply with the following:

```javascript
{
  "Sentiment": "POSITIVE",
  "SentimentScore": {
    "Positive": 0.9985805749893188,
    "Negative": 0.00013431961997412145,
    "Neutral": 0.0008679831516928971,
    "Mixed": 0.00041714494000189006
  }
}
```
