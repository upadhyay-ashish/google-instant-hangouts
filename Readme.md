# Google Instant Hangout

A Ruby wrapper to integrate Google's [Instant Hangout](https://github.com/google/instant-hangouts) - Instant Hangouts lets you easily add Google+ Hangouts to any web page:

A [Sample Application with usage can be found here](https://github.com/ankit8898/google-instant-hangouts-sample) .

## Installation

Add the gem to the Gemfile:

    gem "google-instant-hangouts"    

## Usage

In your JavaScript manifest (e.g. `application.js`):

    //= require google-instant-hangouts


In your `*.html.erb` or `*.html.haml` you can use this helper

    <%= instant_hangout %>
    
### Options :

1) Hangouts-on-Air (HOA) 

   Add `hangout_type: 'onair'` as a option to the helper method
   	
   	<%= instant_hangout hangout_type: 'onair' %>
    
**Note:** Work In Progress
