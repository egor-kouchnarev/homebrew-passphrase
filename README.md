# homebrew-passphrase

A command-line random [passphrase](https://xkcd.com/936/) generator.

### Logic

Uses the [EFF Large Wordlist](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt) (7,776 words) to return a random 4-word passphrase. Accepts an optional length argument within the range of 2 to 16. More information on the dictionary can be found [here](https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases).

## Usage

```
passphrase [2-16]
```

## Installation

### macOS/Linux

1. Install the [Homebrew](https://brew.sh) package manager.
2. Add my repository and install the package:
   
```
brew tap egor-kouchnarev/tap
brew install passphrase
```
