# cput

Having bloated binary file just to change terminal properties is kinda useless when you just can use escape codes... but escape codes are hard to remember... cput fixes that, as just shell scrip wrapper to escape codes it doesnt need to be bloated...

Utility/script to quicky change cursor properties such as color or position.

Tput mode: emulates tput, like: setaf setab sgr0 cols lines cup

Can repleace tput using `patch` subcommand that replaces "tput" with "cput" in selected file
