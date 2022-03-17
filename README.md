
# Why
While developing apps for [Homey](https://homey.app), I've seen a lot of threads in Slack and on the forum, asking questions that should have been answered in the official documentation. Besides that, I've done a lot of experimenting and reading code myself to find out how poorly documented features actually work. Sometimes identifying functionality in the API that might not be documented at all.

For both my own sake as that of others, I decided to start collecting this knowledge in the form of a Wiki.

# What
The [wiki of this repository](/Joolee/Homey-unofficial-documentation/wiki) contains code examples, undocumented features, better explanations of poorly documented features and some tips, tricks and neat utilities for developing an Athom app.

So far, I have only developed on apps using SDKv2. (And SDK1, but that has been deprecated for a while now.) I believe most information on the wiki will work on both SDK2 and SDK3. In cases where I doubt that, I have added a warning. I also have (luckily) never dabbled in apps using 'signals' (Zigbee, Z-Wave, Bluetooth, Infrared and 433Mhz) so the wiki lacks information about those subjects.

# How
In the past, it was possible to browse the source of Athom's apps on [Github](https://github.com/athombv), I found a lot of undocumented tips and tricks that way. Unfortunately, they decided to make all their apps closed source.

It is still possible, to peek into the sources of their [homey-lib](https://github.com/athombv/node-homey-lib) library and the [CLI tooling](https://github.com/athombv/node-homey). You can also sometimes peek in the SDK sources when using a [Javascript debugger](/Joolee/Homey-unofficial-documentation/wiki/Debugging) with breakpoints when running your app.

Athom also sometimes drops tid-bits of information in their public Slack channel and bug-reports in their Github repositories.

# Contribute
You might be able to contribute to the wiki by cloning the source and sending a pull request, but I'm not sure about that. You can always drop me a message through the [issue tracker](/Joolee/Homey-unofficial-documentation/issues) though.

# Disclaimer
I don't work for Athom and don't get paid by Athom. This wiki has nothing to do with them, other than describing their products. Using any undocumented feature is -of course- at your own risk. I can't guarantee the accuracy of the content. If you spot any errors though, please [let me know](/Joolee/Homey-unofficial-documentation/issues)!
