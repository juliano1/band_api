# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Steps
    * rails g scaffold Band name:string
    * rails g model Member name:string band:references
    * bundle add active_model_serializers
    * rails generate serializer band
