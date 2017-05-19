Code convention IDEs settings for different languages
### ActionScript 3
Convention is from [FlexSDK](http://sourceforge.net/adobe/flexsdk/wiki/Coding%20Conventions/)

To import setting from xml file to Idea place this file into this dir *\.IntelliJIdea15\config\codestyles\*

If you don't like to reformat some piece of code in Idea, please, see [this doc](https://www.jetbrains.com/idea/help/reformatting-source-code.html)

Good flow [from stackoverflow](http://stackoverflow.com/questions/946993/intellij-reformat-on-file-save)


InteliJ Settings-->Editor-->Code Style-->Formatter Control (check Enable formatter markers in comments)

// @formatter:off
while (!isStartRepPoint(originalPtsWithMetaPoints[ --beforeSequenceIndex ])) {}
// @formatter:on


