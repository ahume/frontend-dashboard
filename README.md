Frontend Dashboard
==================

Requirements
------------

 * [Bundler](http://gembundler.com/)
 * You will require a `~/.fog` file containing your AWS credentials as described below:

    default:
      aws_access_key_id: _YOUR_KEY_
      aws_secret_access_key: _YOUR_SECRET_
      region: 'eu-west-1'
      
  * Add a `/data` directory to the project root that ruby can write to.

Running
---------

    $ bundle install
    $ rackup
