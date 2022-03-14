# @web4/connect-test

Create connections with peers in the 'connect-test' topic (Demo).

```
npx @web4/connect-test
```

You should see output like:

```
★   ★   ★   ★   ★   ★
  ★   ★   ★   ★   ★
Bitswarm Connect-Test
  ★   ★   ★   ★   ★
★   ★   ★   ★   ★   ★

▶ Testing hole-punchability...
✔ Your network is hole-punchable

ℹ Waiting for connections...

› New connection!
› New connection!
› New connection!
```

That's all it does! It joins the bitswarm under the 'connect-test' topic (hashed by sha256) and then arranges connections. The connections aren't used at all.