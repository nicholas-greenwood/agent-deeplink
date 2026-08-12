# agent deeplink

open local codex and claude code threads from clickable https links

github removes custom URL schemes from markdown, so this https bridge makes local agent threads clickable in pull requests and issues

```text
https://nicholas-greenwood.github.io/agent-deeplink/?v=1#codex/<thread-id>
```

```text
https://nicholas-greenwood.github.io/agent-deeplink/?v=1#claude/<session-id>
```

the id stays in the url fragment and is never sent to the server

i will keep this live until at least 2028
