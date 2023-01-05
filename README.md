# testmail-helper
Command-line program using [Testmail.app](https://testmail.app/) API to see inbox more readably.

## Getting Started
Install packages by pip.
```bash
pip install -r requirements.txt
```

Make a json file which contains api key and namespace of your Testmail.app account.

```JSON
credentials.json
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
python testmail-helper.py

# With tag
python testmail-helper.py --tag your_tag
```

## License

[MIT](https://choosealicense.com/licenses/mit/)