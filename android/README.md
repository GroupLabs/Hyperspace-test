# ARCore Development
ARCore is Google's augmented reality (AR) sofware development kit (SDK). ARCore supports development for iOS, Android, and WebXR (more on this later) platforms. 

## Notes on using ARCore for iOS and WebXR
ARCore's support for iOS is limited (e.g. image tracking is not available - in other words iOS is a second class citizen in all aspects of ARCore). Therefore, we will use ARCore to develop an Android client, but not for the iOS client.

WebXR is currently too immature for any substantial use case. The great thing about our approach is that it is extensivle, meaning that we can add support for WebXR later on as needed.

## Development Guide
It is possible and useful to implement both Kotlin/Java and C features at the same time. It is encouraged to choose whichever language is preferrable for the task. Generally, Kotlin/Java is better for ease-of-development, while C gives more precise control over the hardware. Please be aware of the differences between the Android SDK and NDK if you choose to go down this path.

### ARCore API reference:
    - https://developers.google.com/ar/reference

### Get a feel of how other ARCore apps are built:
    - [Samples](https://developers.google.com/ar/develop/samples)
    - [Codelabs]: (https://codelabs.developers.google.com/?category=ar)