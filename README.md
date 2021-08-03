# forward-backend-errors
Forward backend error codes and show a custom error page


## You will need to create your own .html files for the specific Errors

proxy_intercept_errors - Determines whether proxied responses with codes greater than or equal to 300 should be passed to a client or be intercepted and redirected to nginx for processing with the error_page directive.


Once you have this running in your browser, eachof the endpoints / app1 / app2 / app3 provides a different Response Code. For the Errors, specific error pages should be picked up.
