## Unreleased

## 0.3.0

* Fixes
  * Added `Devise::Async::Model` to use new devise's after_commit hooks to resolve #6 (only devise >=2.1.1)

## 0.2.0

* Enhancements
  * Added `Devise::Async.queue` option to let configure the queue
  the jobs will be enqueued to.

## 0.1.1

* Fixes
  * Changed the way we store the record id in the queue to enforce
  compatibility with diferent ORMs

## 0.1.0

* New
	* Added `Devise::Async.mailer` option to proxy to custom mailers
	* Added `Devise::Async.setup` to allow configuring with blocks

## 0.0.2

* Enhancements
	* Restructured gem to Devise::Async module instead of DeviseAsync.

* Deprecations
	* DeviseAsync::Proxy is now Devise::Async::Proxy
	* DeviseAsync.backend is now Devise::Async.backend

## 0.0.1

* first release
