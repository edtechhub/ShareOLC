Share OLC
=========

Collecting geodata is important, especially in times of crisis. For a good example how geodata and maps can help, have a look at https://hotosm.org.

There are many many apps that can collect geodata, including apps such as WhatsApp. However, when we have collected geodata with colleagues in sub-Saharan Africa, working with health workers in remote areas, there are problems. For example, a member of staff in the head office (e.g., the regional branch of the Ministry of Health) is asked a health worker in a rural area to communicate their location. 

Here are some of the problems that arise:
- The health worker may not know to go outside (as they may not be familiar with how GPS works).
- The health worker may not have connectivity, so their phone doesn't utilise AGPs. They may not know that they need to stay outside for about 15 minutes for the phone to acquire a location.
- When the phone has acquired location, the health worker may not have internet to share the location digitally. Instead, they write it down on paper, or read it out over the phone. When reading out latitude and longitude, it's easy to make errors.

Even if the health worker has internet, most simple applications just share the location. The recipient does not know how accurate the location was. There are of course many more complicated applications that do this, but they are too complicated to use.

The goal for this application is to be as simple as possible, while collecting essential information:
- Location
- Accuracy

while offering advice to the user.

The application is going to be full open source, backwards compatible with earlier versions of Android where possible. We will also post the application to the Google Apps store. 

FAQ
===

__What is OpenLocationCode?__ See https://github.com/google/open-location-code

__Why do you think this app is needed?__ The need for this app is based on personal experience working particularly in Zambia and Ghana, as well as wider experience of working with https://hotosm.org. The requirements for the above app sound simple, and it sounds as if e.g. WhatsApp already does this. However, when you speak with a user over the phone, on a poor phone line, trying to figure out why the app isn't delivery an accurate location, things look very different. 

__The SDK has an example for GeoLocation - can I use that?__ Yes, of course. The app is conceptually very close to the example in the SDK. It just presents itself slightly differently to the user.

__Why Android and not iOS?__ Most phones in Africa and other low-income regions of the world are Android.

__Why Android and not KaiOS?__ We would love to build an app for KaiOS as well.

__Which version of Android?__ The app should be compatible with the lowest version of Android reasonably possible. This is because in low-income countries, many older Android phones are still in use.

__How long do you think the development of this app would take?__ I'm what you might call an inexperienced Android developer (as my main just is something else). However, when I've done Android development in the past, I've tinkered the with SDK examples, and built similar things. To an experienced Android developer, a first version should not take more than a few hours.
