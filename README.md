# gateway

[![Gem Version](https://badge.fury.io/rb/gateway.png)](http://badge.fury.io/rb/gateway)
[![Build Status](https://travis-ci.org/aq1018/gateway.png?branch=master)](https://travis-ci.org/aq1018/gateway)
[![Dependency Status](https://gemnasium.com/aq1018/gateway.png)](https://gemnasium.com/aq1018/gateway)
[![Code Climate](https://codeclimate.com/github/aq1018/gateway.png)](https://codeclimate.com/github/aq1018/gateway)

Gateway is an opinionated generic IO connection manager. It is created to be a manager / wrapper that can provide a uniform behavior across various IO connection types such as HTTP, Memcache, database, or even generic TCP / UDP protocols.

This gem provides a `Gateway::Base` class for other connection types to be built upon. It provides the following features:

* Connection Management. Choose from single, connection pooling, or thread local.
* Error Transform / Handling.
* Timeouts
* Automatic retry
* performance logging
* Newrelic instrumentation. ( If newrelic is loaded. )
* Designed specifically for multi-threaded usage and is completely thread safe.

## Contributing to gateway

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Aaron Qian. See LICENSE.txt for
further details.

