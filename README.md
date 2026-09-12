# Color Switch Rush - YouTube Playables

## Structure
- index.html in root (required)

## SDK Integrations
- Required: firstFrameReady(), gameReady(), IN_PLAYABLES_ENV, isAudioEnabled(), onAudioEnabledChange(), onPause(), onResume(), loadData(), saveData()
- Recommended: getLanguage(), sendScore(), logError()/logWarning()
- Monetization: requestInterstitialAd() on Game Over, requestRewardedAd('continue-after-crash') for revive

## Test
Upload zip to Playables test suite: https://developers.google.com/youtube/gaming/playables/test_suite
