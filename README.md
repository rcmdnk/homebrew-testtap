# homebrew-testtap

A empty tap repository for development purposes on Homebrew.

It is particularly useful for creating new formulas using `brew tap`, which requires a local tap. 
By default, Homebrew now uses API to get formulas, so a local Tap of Homebrew-core does not exist.

In this case, follow these steps:


```
$ brew tap rcmdnk/testtap
$ brew create --tap rcmdnk/testtap [other options] <URL>
```

Then, you can work with a file in `$(brew --repo rcmdnk/testtap)`.
