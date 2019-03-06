# takehome

## Your mission

A client needs to know what is happening on the social networks. All of them. Right now.

The three social networks the client is interested in are:

twitter

facebook

instagram

Because these social networks are so webscale, they don't always respond predictably. The delay in their response almost appears like someone waited for a random integer of seconds before responding!

Also, sometimes they will respond with an error. This error will not be valid JSON. Life's hard sometimes.

The client needs to be able to run your thing, then issue the command:

```
curl localhost:3000
```

And get back a JSON response of the output from the three social networks in the format:

```
{ twitter: [tweets], facebook: [statuses], instagram: [photos] }
```

Order isn't important.

Don't forget to `git push` regularly.

Have fun!
