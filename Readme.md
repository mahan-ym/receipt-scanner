# Reciept Scanner

This project is about scanning restaurants and cafes receipt and extract some features

Features are :

* identify item

* identify item's name

* identify item's price

* identify item's count

after the extraction the result is a json array with this format

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

## structure

- dataset : includes different receipts to train data
- notebook : a jupyter notebook to train the model
