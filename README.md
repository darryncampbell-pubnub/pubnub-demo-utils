# pubnub-demo-utils
Utility files for PubNub demos

## Interactive Demo:

### V1.0:

https://darryncampbell-pubnub.github.io/pubnub-demo-utils/js/interactive-demo-interface/v1/demo-interface.js

### V2.0:

https://darryncampbell-pubnub.github.io/pubnub-demo-utils/js/interactive-demo-interface/v2/demo-interface.js

### Usage:

```javascript
actionCompleted({
  action: 'Reboot any device (it will go offline briefly)',
  debug: false
})
```

## Moderation:

**Note that you should use PubNub functions for server side moderation**

https://darryncampbell-pubnub.github.io/pubnub-demo-utils/js/interactive-demo-interface/clientside-moderation.js

### Usage:

```javascript
var moderatedText = moderate(text);
```
