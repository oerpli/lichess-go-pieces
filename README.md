# lichess-go-pieces
CSS, JS and SVGs for a lichess userstyle/userscript that changes the pieces to go stones ("semi-blind mode")

## History

Once upon a time I've been in a pub with a friend and a Go-board and neither of us could play Go so we decided to play chess with the stones from Go.

Some fun was had back then, as the resulting gameplay was in between blind chess and normal chess (you see the color and that a piece is at a given position but not what kind of piece it is).

Initially developed as [pull-request](https://github.com/ornicar/lila/pull/4059) to be officially implemented on lichess.org, though ornicar suggested to do this as userstyle instead.

So here goes:

* [Userstyle](https://userstyles.org/styles/156409/lichess-pieces-go) (CSS only, use Stylish [FF](https://addons.mozilla.org/en-US/firefox/addon/stylish/)/[Chrome](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en))
* [Userscript](https://greasyfork.org/en/scripts/38979-lichess-pieces-go) (Only injects CSS, use Greasemonkey or Tampermonkey [FF](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)/[Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)

The userscript version is auto generated from the userstyle does basically the same thing (inject the `.user.css`  into the DOM. 
