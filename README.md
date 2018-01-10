# experimentalCardEaseFactor
Adjusts ease factor for cards individually during review an Anki. See: https://eshapard.github.io/anki/thoughts-on-a-new-algorithm-for-anki.html for rationale.

Cards must have more than 4 'review' reviews to be adjusted. Reviews done when the card is in learning or re-learning are not counted.

Important: **You must not use an interval modifier in your deck options**. In other words, your interval modifier must be set to 100% (no change) for all decks.

### Configuration
There are a couple options that can be configured by editing the addon:

1. targetRatio = Set this to whatever success rate you want to aim for (e.g. 0.85 for an 85% success rate)
2. showCardStats = True/False; if True, a pop-up with some card stats will be shown whenever a card is adjusted.

## YesOrNo.py
When using the experimental card ease factor addon, you will not need to choose among hard, good, and easy. Instead, the addon will look at your past review success rate to determine whether the card's ease factor is too hard or too easy. So just use *good* if you remembered and *again* if you forgot.

The YesOrNo.py addon changes your options from Again/Hard/Good/Easy, to Defeat/Victory (where victory is equal to good). The words are configurable in the addon. Note: There is a slot to control the "Show Answer" text, but that isn't implemented yet.

I suggest that you use the YesOrNo addon and that you disable *Show next review time above answer buttons* in Tools > Preferences... Seeing the next review times will just distract you from studying.

IF YOU FIND THIS ADDON HELPFUL, PLEASE CONSIDER MAKING A $1 DONATION
USING THIS LINK: https://paypal.me/eshapard/1
