# Zorn's Xcode Templates

Note: I've only tested this with Xcode 5. Still need to see if Xcode 6 changes anything.

## What's Here

* Copies of all the standard Apple file types templates (minus the `XCTest`ing stuff, I prefer `Kiwi`) but these templates have no copyright clauses in the headers or implementation files!
* A simple `Kiwi` template.

## Install

Download these and store them in your home directory at:

`/Users/{YourUsername}/Library/Developer/Xcode/Templates/File Templates/{GroupName}`

## Background Info

Most of the info I use to do this I got from this question on Stack Overflow:

<http://stackoverflow.com/questions/20311839/change-copyright-top-comment-header-on-all-new-files-in-xcode-5>

The stuff you need to know: Xcode 5 stores it's templates in it's bundle at:

`Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/File Templates`
 
 and
 
`Xcode.app/Contents/Developer/Library/Xcode/Templates/File Templates`



I leave the details of the template bundle format as a exercise for the reader. They aren't too hard to get your head around. I'd start with the apple standard `Protocol` one as it seems to be the smiliest.