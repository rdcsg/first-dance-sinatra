About Capybara
==============
"Capybara is a web-based automation and integration testing framework for rack based web applications used for creating functional tests that simulate how users would interact with your application.

The main characteristic that developers are aiming for is the ability to have tests that are modular, easy to write, and easy to maintain. This is especially true in Agile/TDD environments where writing tests is second nature. These tests are expected to give good and fast feedback on code quality. As time goes by, the number of tests grows and it can be a real nightmare to maintain the tests, especially when the tests are not modular and simple enough."



About Rack
==========
Rack is a middle layer framework that works between our web apps and the application servers and we can disregard which server it is as long as we know how to talk to Rack, cause Rack manages the calls and API's of each server. So that makes Rack a communication's interface between web application and web frameworks on the one hand and the server side applications on the other hand.

Rails was actually built in Rack, as well as Sinatra - so they are both Rack apps, whereas Rack itself is a Ruby package.



About Launchy
=============
"Launchy is helper class for launching cross-platform applications in a fire and forget manner. There are application concepts (browser, email client, etc) that are common across all platforms, and they may be launched differently on each platform. Launchy is here to make a common approach to launching external application from within ruby programs."

This means that Launcy is a middle layer too, helping us to launch any programs from within Ruby on any application platform, so we don't have to worry how the different platforms actually do it.

And ofc it's made in Ruby. =)



About Shotgun
=============
Shotgun is a small gem that enables you to reload (hence the name) the application server with some reloaded code instead of reloading the entire thing. Working iteratively like we do this saves a lot of time and resources.

"Shotgun is a small Ruby gem that makes it easier to develop Rack-based Ruby web applications locally by starting Rack with automatic code reloading. A gem is just a library of code that developers wrote and made free and available to the public. This gem lets us start Rack to have a development server running to test our app.

When you start an application with shotgun, all of your application code will be reloaded upon every request. That means if you change anything in your code and save it, when you hit 'Refresh' in your browser, your application will respond with the latest version of your code."



About HTML5
===========
In order for it to work a HTML5 page needs to have the main tags html, head, title, body - and to have it comply with HTML5 standards and thus making it a true HTML5 page it needs to have the appropriate document type definition.




About Assets
============
Assets are all our supporting files and documents that help us create the web page contents or are a part of the content, but that are not part of the central enginge that makes the page happen. We will reference the assets to make them part of the content but other than that they are not needed in the intelligence and logic of the page. This is a modified truth, as javascript and css files do have their own logic to generate content.
