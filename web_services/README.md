# Web Services Project

At IZEA we are creating a set services that power the IZEAx ecosystem. The
following project is build a simple service that leverages some of the 
technologies that we use as part of our reference architecture.

If any special requirements have been conveyed to you from your interview
team, they supercede the following.

## Requirements

- [ ] Create a webservice using Java, Ruby, or Node.js that has a single 
      endpoint.
- [ ] The endpoint should receive as a parameter a string and return that 
      string reversed. For example, if the endpoint is given the string 
      "izea" it should return "aezi".
- [ ] Your service must be packagable as a Docker container and your 
      submission should contain all files necessary to build the container.
- [ ] Your submission should contain a README file that spells out the exact 
      steps necessary to build and run the container. It should also provide 
      instructions for how to query the webservice.

Design of the API endpoint including paths, structure, and format is up to 
you. Decisions on how to structure the code and what frameworks to use are 
up to you as well.

## Bonus

- [ ] Add another endpoint to your service that allows for the bulk (hundreds) 
      submission of strings.
- [ ] Build a frontend for the service in Ember.js that allows users to submit
      strings to reverse in a form and see the results.
- [ ] Extend your front end to allow a text file full of reversible words to be 
      submitted to the bulk API. Results can be rendered directly on the page
      or downloaded as a text file.

