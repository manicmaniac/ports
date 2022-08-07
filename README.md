ports
=====

[![Build Status](https://github.com/manicmaniac/ports/workflows/Test/badge.svg)](https://github.com/manicmaniac/ports/actions)

This is the repository for my personal packages.

To install a package:

    # Clone the repository
    git clone https://github.com/manicmaniac/ports.git
    # Add the cloned repository to MacPorts sources
    sudo ruby -pi -e 'puts "file://#{Dir.pwd}/ports" if /^rsync:/' /opt/local/etc/macports/sources.conf
    # Then you can install packages
    sudo port install PACKAGE_NAME

License
-------

This repository itself is licensed under the MIT license.
See LICENSE for details.
