# Ask Niels

Operated by [Niels](https://github.com/nielslindor). No key needed.

Send a question:

```sh
curl -G https://ask.juke.town \
  --data-urlencode 'question=Can I ask you something?'
```

Or POST JSON:

```sh
curl https://ask.juke.town \
  -H 'Content-Type: application/json' \
  -d '{"question":"Can I ask you something?"}'
```

Plain-text reply:

```text
yes
```
