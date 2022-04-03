## This is a 36 minute lab to excercise the use of NLP 
## This lab is made out of 5 units.  Please follow the instructions and links below to complete the lab.
## Please ask questions during the lab at any time to both your instructors.

# Analyze Text with the Language Service

Start here https://docs.microsoft.com/en-us/learn/modules/analyze-text-with-text-analytics-service/

### Introduction (3 min)

### Get Started with Text Analysis (10 min)

### Alanlyse Text (20 min)

### Knowledge check (2 min)

### Summary (1 min)

## Endpoints and test JSON

### Key Phrases Link:
<https://docs.microsoft.com/en-us/rest/api/cognitiveservices-textanalytics/3.0/key-phrases/key-phrases>

```json
{
"documents": [
{
"id": "1",
"text": "The MGM hotel is a great place. The staff were very friendly. The service was amazing"
},
{
"id": "2",
"text": "We didn't enjoy our stay at the Circus Circus. The service was not up to the mark"
},
{
"id": "3",
"text": "The hotel is in Las Vegas. The room had a TV. The hotel had 4 pools"
}
]
}
```

### Languages
Endpoint:
<https://docs.microsoft.com/en-us/rest/api/cognitiveservices-textanalytics/3.0/key-phrases/Languages>

```json
{
"documents": [
{
"id": "1",
"text": "The MGM hotel is a great place. The staff were very friendly. The service was amazing"
},
{
"id": "2",
"text": "We didn't enjoy our stay at the Circus Circus. The service was not up to the mark"
},
{
"id": "3",
"text": "The hotel is in Las Vegas. The room had a TV. The hotel had 4 pools"
}
]
}
```

### Sentiments
Endpoint
<https://docs.microsoft.com/en-us/rest/api/cognitiveservices-textanalytics/3.0/key-phrases/Sentiment>

```json
{
"documents": [
{
"id": "1",
"text": "The MGM hotel is a great place. The staff were very friendly. The service was amazing"
},
{
"id": "2",
"text": "We didn't enjoy our stay at the Circus Circus. The service was not up to the mark"
},
{
"id": "3",
"text": "The hotel is in Las Vegas. The room had a TV. The hotel had 4 pools"
}
]
}
```

### Entity Recognition

Endpoint
<https://docs.microsoft.com/en-us/rest/api/cognitiveservices-textanalytics/3.0/entities-recognition-general/entities-recognition-general>

```json
{
"documents": [
{
"language": "en",
"id": "1",
"text": " Last night we had dinner at the StripSteak restaurant inside of the Mandalay Bay Hotel, the Wagyu steak was incredible"
}]
}
```

### Translator

Endpoint:
<https://api.cognitive.microsofttranslator.com/translate?api-version=3.0&to=es>

```json
[{
   Text: "The MGM Hotel is amazing"
}]
```

### Speech To Text

<https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/#features>

### Text to Speech

<https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/rest-text-to-speech>

<https://github.com/Azure-Samples/cognitive-services-speech-sdk>


