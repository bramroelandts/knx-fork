# Fork of JavaScript KNX library

- Original library available [on BitBucket](https://bitbucket.org/ekarak/knx.js/src/master/).
- This repository was forked to fix an issue in the disconnection logic.
- The idleTimer was not cleaned up corrrectly in the FSM. This would cause the stack to re-initialize the connection and start throwing errors all over the place.
- See [this issue](https://bitbucket.org/ekarak/knx.js/issues/87/fsm-disconnect-not-correctly-closing/) for more information.
