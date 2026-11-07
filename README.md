# Yoyo Rocket demo

- Russian: https://w5sk.github.io/yoyo-rocket-demo/?lang=ru
- English: https://w5sk.github.io/yoyo-rocket-demo/?lang=en

On desktop, player bets are always on the left. Opening chat hides the bet list and shows chat on the right; closing chat restores the list and its selected filter. On mobile, the game and both bet controls fill the first screen. Player bets follow directly below and are reached by scrolling the page. There is no separate button for opening the list. Mobile chat fills the screen and locks background scrolling.

Charcoal surfaces, rectangular blue controls and a blue jetpack pilot. All / My / Top filters, previous rounds, own bets and next-round queues follow the demo engine. The other 28 participants are clearly labeled simulated activity and never affect the wallet or round results. Chat is local to the tab: 160 characters per message, up to 60 messages, no communication between visitors or persistence after reload.

Auto cash-out targets from 1.00 to 999.99 fit without horizontal input scrolling. The 21 browser scenarios include six complete Android/iPhone profiles checked in Russian and English using Chromium/WebKit and touch input. The first screen, normal page scrolling to the bet list, desktop chat replacement and independent cash-outs are covered. These are emulated profiles, not physical-device certification.

Virtual demo coins only. No payments or real money. The pilot sprite is a 58 KB WebP; previous asset URLs remain available for cached clients.
Source revision: b8266a217b544b81790ef64e7b98a83dcd81cf15.
The speaker control is visible beside round history on phones and in the header on desktop. Tap it once to enable sound; the choice is remembered. Effects are louder, touch activation and audio interruption recovery are handled. Audio samples and recovery were verified in desktop/Android Chromium profiles. Windows WebKit lacks Web Audio, so iPhone profiles verify the control and unavailable-audio fallback only; physical iPhone audio remains unverified.
