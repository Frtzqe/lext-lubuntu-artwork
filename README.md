WORK IN PROGRESS

# lext-lubuntu-artwork-latest - Lubuntu-Arc theming for LXQt
This repository is intended for use by AUR. See package 'lubuntu-artwork'. Mentioned package has a problem (or, it is not maintained) and can't be used anymore without tweaking.

Lubuntu artwork is available at http://archive.ubuntu.com/ubuntu/pool/universe/l/lubuntu-artwork, however there is no such thing as a 'latest' release alias. 

The 'lubuntu-artwork' packages uses a specific package identifier. Each update of the Lubuntu-Arc comes with its own unique package identifier (e.g. 24.04.3). This is currently (at time of writing) the package version that is expected to be available from 'upstream'. 

This implies that aforementioned package should be updated regularily (for the semiannual releases, and even more than twice a year due minor changes to a release). 

A complicating factor is that on the given source URL, only the latest minor version of a release is kept. In my earlier example this is 24.04.6 (available) and not 24.04.3 (as needed).

Since the 'lubuntu-artwork' package is not maintained, installation of the package will fail. 

This is where 'lext-lubuntu-artwork-latest' may help. It allows to load the lastest version of the Lubuntu-Arc theming onto your system, with AUR. 

For most use cases this will suffice. If you explictly need an earlier version (as available on te source URL), you need to tweak the PKGBUILD file, as described on the 'lubuntu-artwork' page on AUR. 
