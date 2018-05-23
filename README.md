# KeyboardAutoswitch

Change input method on macOS automatically based on current application. Just a concept project for my own personal use.

Meant to make `keyboardautoswitch` way, didn't work, so made workaround and made `checkWindow`. Then figured out what's wrong, made `keyboardautoswitch` right.

- it works, anyway.
- they use exactly same concept with different methods.
- caveat: excessive cpu usage
  `System Events` process use app. 10% of cpu resources on Macbook Air 2012 when idle interval is set to 1s. Number increases up to 50% when interval is set to .1s.