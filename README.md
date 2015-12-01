![Realm](https://github.com/realm/realm-dotnet/raw/master/logo.png)

Realm is a mobile database that runs directly inside phones, tablets or wearables.
This repository holds the source code for the C# versions of Realm, for use in Xamarin and generic C#.

## Features

* **Mobile-first:** Realm is the first database built from the ground up to run directly inside phones, tablets and wearables.
* **Simple:** Data is directly [exposed as objects](https://realm.io/docs/xamarin/latest/#models) and [queryable by code](https://realm.io/docs/xamarin/latest/#queries), removing the need for ORM's riddled with performance & maintenance issues. Plus, we've worked hard to [keep our API down to just 4 common classes](https://realm.io/docs/xamarin/latest/api/) (Object, List, Query and Realms) and 1 utility class (Migrations): most of our users pick it up intuitively, getting simple apps up & running in minutes.
* **Modern:** Realm supports relationships, generics, vectorization and modern C# idioms.
* **Fast:** Realm is faster than even raw SQLite on common operations, while maintaining an extremely rich feature set.

## Getting Started

Please see the detailed instructions in our docs to add [Realm](https://realm.io/docs/xamarin/latest/#installation) to your Xcode project.

## Documentation

The documentation can be found at [realm.io/docs/xamarin/latest](https://realm.io/docs/xamarin/latest).  
The API reference is located at [realm.io/docs/xamarin/latest/api](https://realm.io/docs/xamarin/latest/api).

## Getting Help

- **Need help with your code?**: Look for previous questions on the  [#realm tag](https://stackoverflow.com/questions/tagged/realm?sort=newest) — or [ask a new question](https://stackoverflow.com/questions/ask?tags=realm). We activtely monitor & answer questions on SO!
- **Have a bug to report?** [Open an issue](https://github.com/realm/realm-dotnet/issues/new). If possible, include the version of Realm, a full log, the Realm file, and a project that shows the issue.
- **Have a feature request?** [Open an issue](https://github.com/realm/realm-dotnet/issues/new). Tell us what the feature should do, and why you want the feature.
- Sign up for our [**Community Newsletter**](http://eepurl.com/VEKCn) to get regular tips, learn about other use-cases and get alerted of blogposts and tutorials about Realm.

## Building Realm

In case you don't want to use the precompiled version from NuGet, you can build Realm yourself from source.

Prerequisites:

* **Apple via Xamarin:** Xamarin IOS Indie license or above. 
* **Android via Xamarin:** Xamarin Android Indie license or above
* **Windows platforms** Visual Studio 2013 or higher, recommended 2015
* Building Realm Xamarin for IOS also requires Xcode 7.1.
* Building Realm documentation requires [Doxygen](http:/www.doxygen.org)


We support the current Xamarin _Stable_ and _Beta_ update channels, at the time of release this corresponded to:

* Xamarin iOS version 9.2.1.51
* Xamarin Android version 6.0.0.34
* Xamarin Studio version 5.10


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details!

## License

Realm Dotnet is published under the Apache 2.0 license.  
The underlying core is available under the [Realm Core Binary License](https://github.com/realm/realm-dotnet/blob/master/LICENSE#L210-L243) while we [work to open-source it under the Apache 2.0 license](https://realm.io/docs/xamarin/latest/#faq).

**This product is not being made available to any person located in Cuba, Iran,
North Korea, Sudan, Syria or the Crimea region, or to any other person that is
not eligible to receive the product under U.S. law.**

## Feedback

**_If you use Realm and are happy with it, all we ask is that you please consider sending out a tweet mentioning [@realm](https://twitter.com/realm), announce your app on [our mailing-list](https://groups.google.com/forum/#!forum/realm-dotnet), or email [help@realm.io](mailto:help@realm.io) to let us know about it!_**

**_And if you don't like it, please let us know what you would like improved, so we can fix it!_**

![analytics](https://ga-beacon.appspot.com/UA-50247013-2/realm-dotnet/README?pixel)