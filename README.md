<div align=center>
<img src="https://github.com/AudioKit/Cookbook/raw/main/Cookbook/Cookbook/Assets.xcassets/audiokit-icon.imageset/audiokit-icon.png" width="20%"/>
  NEW Fetures 
🚀 New Features Added

Continuous Listening Mode (Loop Dictation)

Toggle switch to keep microphone capture alive across speech breaks and silence pauses.
Automatically re-arms recognition after utterance completion or silence timeout without needing manual re-tapping.

Real-Time 7-Bar Audio Waveform Equalizer

An animated multi-bar voice visualizer that bounces dynamically in response to incoming microphone audio pitch/volume levels (onSpeechVolumeChanged).

Session Duration Timer

Live recording badge displaying elapsed session time in tabular minutes and seconds (00:00).

Speech Metrics Dashboard

Instant computation of Word Count, Character Count, and active Language Tag for recognized text.

Saved Notes & Transcript History Manager

Save Note: Stores recognized speech into a timestamped, word-counted history list.
Native Share: Opens the device's native share sheet (Share.share) to export transcripts directly to Messages, WhatsApp, Email, or Slack.
Delete / Clear All: Manage saved notes individually or wipe history.

Multi-Hypothesis Candidate Selector

Displays alternate recognition interpretations from the native engine.
Tap any alternate candidate (#2, #3, etc.) to promote it to the primary transcript.

Expanded Languages & Custom Locale Selector

Expanded presets: English (US & UK), Spanish, French, German, Italian, Portuguese, Japanese, Mandarin Chinese, Hindi, Arabic, and Korean.
Custom Locale Picker: Input field allowing testing of any custom BCP-47 locale tag (e.g. nl-NL, sv-SE, tr-TR).

Platform & Engine Diagnostics

Detects and lists installed speech recognition services on Android via Voice.getSpeechRecognitionServices(), with platform version inspection.

Dark Mode / Light Mode Theme Switcher

Instant toggle between light mode and high-contrast dark mode.
  
# AudioKit

[![](https://github.com/AudioKit/AudioKit/actions/workflows/swift.yml/badge.svg)](https://github.com/AudioKit/AudioKit/actions?query=workflow%3ACI) 
[![License](https://img.shields.io/cocoapods/l/AudioKit)](https://github.com/AudioKit/AudioKit/blob/main/LICENSE)
[![Platform](https://img.shields.io/cocoapods/p/AudioKit)](https://github.com/AudioKit/AudioKit/)
[![Reviewed by Hound](https://img.shields.io/badge/Reviewed_by-Hound-8E64B0.svg)](https://houndci.com)

</div>

AudioKit is an audio synthesis, processing, and analysis platform for iOS, macOS (including Catalyst), and tvOS.

## Installation

Using Xcode, you can add AudioKit and any of the other AudioKit libraries using _Collections_:

1. Select `File` -> `Add Package Dependencies...`
2. Click the `+` icon in the bottom left corner of the `Collections` sidebar on the left.
3. Select `Add Package Collection...` from the pop-up menu, which should open a dialog box.
4. Enter `https://swiftpackageindex.com/AudioKit/collection.json` as the URL and click the `Load`-button.
5. Now you can add any of the AudioKit Packages you need and read about what they do, right from within Xcode.

## Documentation

Docs appear on the [AudioKit.io Web Site](https://audiokit.io/). You can also generate the documentation in Xcode by pulling down the Product menu and choosing "Build Documentation".

## Examples

The [AudioKit Cookbook](https://github.com/AudioKit/Cookbook) contains many recipes for simple uses for AudioKit components.

## Getting help

1. Post your problem to [StackOverflow with the #AudioKit hashtag](https://stackoverflow.com/questions/tagged/audiokit).

2. Once you are sure the problem is not in your implementation, but in AudioKit itself, you can open a [Github Issue](https://github.com/audiokit/AudioKit/issues).

3. If you, your team or your company is using AudioKit, please consider [sponsoring Aure on Github Sponsors](https://github.com/sponsors/aure).
