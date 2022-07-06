Simpler
Simpler is a little web framework written in Ruby language. It's compatible with Rack interface and intended to learn how web frameworks work in general.

The application overview
Simpler application is a singleton instance of the Simpler::Application class. For convenience it can be obtained by calling Simpler.application method. This instance holds all the routes and responds to call method which is required by the Rack interface.

simpler