<h1 align="center">
  <br>
  <img src="!Documentation/Logo/RhythmLogo.png" alt="Rhythm" width="500">
  <br>
</h1>

<h3 align="center">A collection of custom nodes for <a href="http://dynamobim.org/" target="_blank">Dynamo</a>.</h4>


If you appreciate the work put into this free package, please vote in support of it on Dynamo's package manager. 

 _If you feel so inclined, here is a method to donate to this open source project_

 <a href="https://www.buymeacoffee.com/j0hnp" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Current Version
Rhythm is currently built against the latest Dynamo stable build. At this time that is 2.0.3.

## Known Issues
- Nodes that interact with background opened documents take some more consideration. This includes running Dynamo graphs that use them in manual run mode and often times closing and opening dynamo after the process is complete. The reason this happens is Dynamo has limited document switching capability and we are exploiting this with those nodes. (Included Nodes: Applications.OpenDocumentFile, Applications.CloseDocument)

## Contributors
This package is currently managed by author of http://sixtysecondrevit.com.

## Updates
Since there is not currently an update notification process on Dynamo's package manager, I post notifications for updates on twitter.
[![](https://img.shields.io/twitter/follow/60secondrevit.svg?label=Follow&style=social)](https://twitter.com/60secondrevit)

## Examples
Examples will be available on the [wiki](https://github.com/johnpierson/RhythmForDynamo/wiki) soon,

## Help improve Rhythm
If you're interested in contributing to Rhythm, just submit a [pull request](https://github.com/sixtysecondrevit/RhythmForDynamo/pulls).

## Installation
Rhythm is available through Dynamo's built-in package manager. This provides the simplest installation for most users. If you are interested in manual install, there are some fabulous resources out there describing how to build your own Dynamo package.

## Thank you!

## What is with all the removals of DYFs?!!
With Dynamo 2.0 comes a fundamental file format change that makes anything that is a DYF or DYN (the filetypes that Dynamo uses) not backward compatible. This forced me to choose between two options. Option 1: Have 2 versions of Rhythm for each major version of Dynamo, eg. “Rhythm for Dynamo 1.x” and “Rhythm for Dynamo 2.x”. Option2: Continue my long term goals of migrating Rhythm to be fully “Zero Touch” c# code. I went with option 2 as it provides a more stable product and further compatibility.
