# Localizing Floor

Thanks for helping us to localize Floor! 🥳

## Voice, tone & brevity
The Floor voice is friendly, informal and informational.

In order to fit in an app originally designed with English language placeholders, favor the shortest version of the translation that can make idiomatic sense. Long strings will likely cause the UI to layout poorly.

## Language Files
The Floor app uses Xcode localization files to localize _every_ String in the app. 

`.xcloc` files are a folder structure of XML files which _can_ be edited manually but are much easier to edit on a Mac, by opening the File in Xcode.

<img width="1064" alt="CleanShot 2022-02-03 at 13 50 58@2x" src="https://user-images.githubusercontent.com/1068437/152409247-12e8e7f0-03f6-4db9-9d0d-10148a9bfee0.png">

You can edit the localized string for a particular language by opening the appropriate `.xcloc` file in Xcode, and then editing the third column with your suggested localization.

<img width="1158" alt="CleanShot 2022-02-03 at 13 52 46@2x" src="https://user-images.githubusercontent.com/1068437/152409562-1dcbcaae-2e6e-453a-b298-258a1d8db983.png">


## Contributing
To contribute you will need access to a Mac, with Xcode 13+.

* Clone this repository
* Create a new branch `git checkout -b yourname/language`
* Open the xcloc file in Xcode
* Add your localizations!
* Commit your changes `git commit -am <your change message>`
* Push your changes `git push origin yourname/language`
* Open a Pull Request

## Approval / Verification
All contributions will be subject to verification.

Want to verify a pending localization, [view pending localizations that need verification](https://github.com/floornfts/localization/labels/verification-needed)

## Weird strings?
There are a number of "format" strings that express how numbers will be displayed e.g. `#%@`. Unless you know what you're trying to achieve, it's safe to ignore these and leave them untranslated.

These:

<img width="601" alt="CleanShot 2022-02-03 at 15 27 36@2x" src="https://user-images.githubusercontent.com/1068437/152423524-74476f47-7738-442c-8fe9-e673ce88a7c0.png">

## Adding new languages?
Want a language that's not included?

Either... 
1. Create an issue and add the `new-langauge` label or...
2. Create a copy of one of the English language and change to the language code you'd like. 

Feel free to jump into the discord to discuss either of these floornfts.io/discord
