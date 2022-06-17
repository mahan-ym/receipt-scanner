# Reciept Scanner

This project is about scanning restaurants and cafes receipts and extract some features

Features are :

* identify item

* identify item's name

* identify item's price

* identify item's count

after feature extraction an ocr turn the text in the image in to a json array with the following format:

```json
{
    "items": [
        {
            "name": "test",
            "price": 1234,
            "count": 2
        },
        {
            "name": "test2",
            "price": 4321,
            "count": 1
        }
    ]
}
```

## problem solving steps:
- [ ] feature extraction
- [ ] detect language (english/persian)
- [ ] run persian or english ocr
- [ ] parse the raw data into the structured json array
- [ ] convert the project to a django web API

## structure

- dataset : includes different receipts to train data
- notebook : a jupyter notebook implementation of the project
