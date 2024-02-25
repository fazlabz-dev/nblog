# NBlog
An open standard for exchanging messages.

## Demonstration
Posts are stored in a JSON object array.

```json
[
  {
    "id": "1",
    "date": "12-05-2024",
    "content": "first"
  },
  {
    "id": "2",
    "date": "12-05-2024",
    "content": "second"
  }
]
```

* `id` - post identifier, it can be either a number or a string.
* `date` - date written in the following format: `DD-MM-YYYY`.
* `content` - post content, can use Markdown.

## License
The specification is licensed under [Unlicense](LICENSE), meaning it's public domain.
