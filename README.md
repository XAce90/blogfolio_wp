# blogfolio_wp
This is where we manage the WordPress code that powers the content displayed in the Blogfolio

# Getting Started

## Installation
> TODO

## How to Run
1. Open this project in your favorite code editor.
2. Turn on WampServer
3. Navigate to `localhost/blogfolio/wp-admin`. Note that going to just `localhost/blogfolio` will redirect you to the live `caseyjamesperno.com` site.
4. Log in using the same credentials you would use for the live admin.
5. All changes you made in this project should now show up on this local environment!

## How to Deploy
1. Push your changes to the repository.
2. Open up FileZilla or some FTP client.
3. Connect to the server where the WordPress instance is running.
4. Copy over the appropriate files (will likely be in mu-plugins).
5. Check it on live!

## Dependencies

The front end is being updated to use GraphQL instead of the REST API, but in order for WordPress to run a GraphQL server, you need the following plugins:

1. [WP GraphQL](https://wordpress.org/plugins/wp-graphql/)
2. [WP Gratsby](https://wordpress.org/plugins/wp-gatsby/)
3. [WPGraphQL for Advanced Custom Fields](https://wpgraphql.com/acf)

Unfortunately WPGraphQL for Advanced Custom Fields is not yet available on the WordPress Repository, so it will need to be uploaded via FTP.