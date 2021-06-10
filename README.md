# homebrew-custom-versions
Contains custom homebrew formula versions to aren't available anymore in the standard tap.


## Creation of a new formula
To create a new formula perform the following steps (e.g. for the groovysdk version 2.4.12)

```
brew extract --version=2.4.12 groovysdk oehmiche/homebrew-custom-formula

# stores the formula at
# /usr/local/Homebrew/Library/Taps/oehmiche/homebrew-custom-versions/Formula/groovysdk@2.4.12.rb
```

```
brew install groovysdk@2.4.12
```

Push the new formula to github.
