a port of
[snakecoin](https://gist.github.com/aunyks/47d157f8bc7d1829a729c2a6a919c173) to
JS.

I'm trying on this to learn more about what a blockchain even is.

Try `curl localhost:4000/transaction -H "Content-Type: application/json" -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'`

And also `curl /mine` and `curl /blocks`