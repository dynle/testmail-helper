# testmail-helper
Command-line program using [Testmail.app](https://testmail.app/) API to see inbox more readably.

## Getting Started
Install packages by pip.
```bash
$ pip install -r requirements.txt
```

Edit the json file which contains api key and namespace of your Testmail.app account.

[credentials.json](credentials.json)
```json
{
  "myAccount": {
    "apiKey" : "your api key",
    "namespace" : "your namespace"
  }
}
```
## Usage
```bash
# No tag
$ python testmail-helper.py

# With tag
$ python testmail-helper.py --tag your_tag
```

## Outputs
```
INBOX:

----------------------------------
From: 
Subject:
Time:
Testmail.app Tag:
Content:

----------------------------------
...
```

## License

[MIT](https://choosealicense.com/licenses/mit/)