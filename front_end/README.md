# Ember.js Project

We've put your soft skills to the test, now we want to see some dope code! For this part of the interview, we would like you to create a small Ember.js app that requests and shows data from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/) (Docs can be found [here](https://github.com/typicode/json-server)). We suggest using the addon [ember-ajax](https://github.com/ember-cli/ember-ajax) to talk to this API.

If any special requirements have been conveyed to you from your interview
team, they supersede the following.

## Requirements

- [ ] Display a paginated list of post titles. The data should be retrieved from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/), and there should be pagination controls to retrieve additional pages of data.
- [ ] Each post should be able to toggle a modal that is populated with the rest of that post's data. You should also include the data of the user related to that post. Make this look & behave however you want, but it should not trigger a full route transition.
- [ ] We are not providing a mock for this, you will need to figure out a design that you feel represents the best user experience.
- [ ] Do not use a front end framework such as bootstrap, but it's fine to use a utility framework like tailwind or neat.
- [ ] The UI should be fairly responsive.
- [ ] Write tests that prove your functionality works.

## Bonus Points
- [ ] Use [ember-cli-sass](https://github.com/aexmachina/ember-cli-sass) instead of vanilla CSS to style your app.
- [ ] Use [ember-test-selectors](https://github.com/simplabs/ember-test-selectors) to isolate how you select elements in tests from your styling code and [ember-cli-mirage](https://www.ember-cli-mirage.com/) to isolate your tests from talking to a real API on the internet.

If you have any questions about the requirements, please feel free to reach out to your interview
team.
