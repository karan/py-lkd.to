py-lkd.to
=========

py-lkd.to is a minimal Python wrapper for [lkd.to API](http://lkd.to/api).

| Build Status | Test Coverage | Version | Download |
| ------------ | ------------- | ------- | -------- |
| [![Build Status](https://travis-ci.org/karan/py-lkd.to.png?branch=master)](https://travis-ci.org/karan/py-lkd.to) | [![Coverage Status](https://coveralls.io/repos/karan/py-lkd.to/badge.png)](https://coveralls.io/r/karan/py-lkd.to) | [![Version](https://pypip.in/v/lkd/badge.png)](https://crate.io/packages/lkd/) | [![Downloads](https://pypip.in/d/lkd/badge.png)](https://crate.io/packages/lkd/) |

Installation
------------

    pip install lkd

Dependencies
------------

**requests**

    pip install requests
    
Usage
------

    from lkd import lkd
    
    karan = lkd('karan')
    print karan.about()['realname']
