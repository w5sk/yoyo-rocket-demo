# Yoyo Rocket demo

Eight working design directions: https://w5sk.github.io/yoyo-rocket-demo/docs/design-review/

Use ?lang=ru&design=1 through ?design=8 (English: lang=en). The default is option 1 while a final direction is being selected. All options have one visible bet panel, the blue pilot, demo bets and local chat. Background music and its controls are removed; short game effects remain.

Desktop player bets appear on the left and are replaced by chat when it opens. On mobile the game fills the first viewport and the player feed follows below; chat opens fullscreen. Virtual demo coins only, no payments. Other participants are simulated and chat is local to this tab.

Screenshots were captured from the working interface on desktop and an Android touch profile. All eight layouts were also checked with iPhone WebKit at widths 320, 390 and 428. Single betting, auto cash-out, RU/EN, chat and no-music checks passed on desktop Chromium, Pixel 7 and iPhone 13 emulation. Physical devices were not tested.

Source revision: 383f726f65b981ebf669bea1c136766192c38654.
Old hashed assets remain available for cached clients.
