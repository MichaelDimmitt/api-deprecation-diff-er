# api_deprecation_diff-er
a gem to ensure APIs are working correctly with your code.

# Feature 1
Every time we run a test suite... this runs.
<br>Or instead of `rspec spec`, think `apicheck spec` to perform this action..

The application works by having a Programmer define a stable API key scrape... 
<br>Simular to an openapijson.
<br>Then the program scrapes the current api state. 

Pattern Match.
<br>Any key change... a single character difference or new keys or removed keys.

Upon conflict, Display the diff between 
<br>Previous stable programmer defined API key scrape and the current API key scrape.
<br>display the whole hash
<br>if there is a diff that can be found display other wise display whole hash.

# Feature 2 
ping API status,
<br>gather an update on the health.  

# Feature 3
if there is a diff/conflict:
<br>api calls, return each one and find if they return nil
<br>basically test that api call. 
<br>display in an additional view next to the diff's the methods of your program that broke.
# Feature 4
search your entire program for lines that match those key names.
<br>display in an additional view the lines that contain those keynames and the file path discovery location.

# Feature 5


Powered by Ryan Murphy and Michael Dimmitt.
