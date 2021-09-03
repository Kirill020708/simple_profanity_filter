# simple_profanity_filter
An easy-to-use library for detecting profanity in texts. Russian language is supported out of the box. Disguised curses are recognized effectively.

Installation:
pip install simple_profanity_filter

Usage:
bool contain_profanity(str)
returns True if sentence contains russian bad word, else otherwise returns False
Also works if, for example, you replace russian letter with it's english analogue
