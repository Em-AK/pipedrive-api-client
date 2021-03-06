# pipedrive-api-client

## Credits

This gem is based on pipedrive-ruby by @GeneralScripting. Since that gem doesn't seem active anymore and the PR's don't get merged I created this one and implemented some of the PR's needed to use the Pipedrive API. 

## Installation

    gem install pipedrive-api-client

## Usage

    require 'pipedrive-api-client'
    Pipedrive.authenticate( YOUR_API_TOKEN )
    Pipedrive::Deal.find( DEAL_ID )

## API Calls
    Pipedrive::Deal.create( params )
    Pipedrive::Deal.find( <ID> )

    Pipedrive::Organization.create( params )
    Pipedrive::Organization.find( <ID> )

    Pipedrive::Person.create( params )
    Pipedrive::Person.find( <ID >)

    Pipedrive::Note.create( params )

You can check some of the calls at https://developers.pipedrive.com/v1


## Contributing to pipedrive-api-client

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## License

This gem is released under the [MIT License](http://www.opensource.org/licenses/MIT).
