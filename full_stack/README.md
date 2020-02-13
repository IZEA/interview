# Full Stack Project

At IZEA we have a set of services that power the IZEA ecosystem and Unity Suite. For this project, we would like you to build a link shortening service. This service will use some of the technology we use in our reference architecture.

>  If any special requirements have been conveyed to you from your interview team, they supercede the following.

## Requirements

### Service

* Create a web service in either **Ruby** or **Node.js**.
* The service should provide a route to create new links.
	* A new link should specify a `target_url`.
	* The route should respond with an `id`, `tiny_url`, and `target_url`.
* The service should also provide a route that looks up `tiny_url` and redirects to `target_url`.
	* As an example, `http://your.service/{tiny_url}`.
* You can assume that the constratints on `tiny_url` are as follows:
	* Must be a constant number of characters in length.
	* Must use an alphabet that is easily encoded.

### Packaging and Deployment

* Your submission should be packaged as a Docker container.
* Your submission must contain a `README.md` that contains instructions on how to build, test, and run your service.
* If youre service requires any additional services (like a database, etc) please use `docker-compose` to orchestrate.

## Guidelines

* Design of the service's API, including paths, structure, and format is up to you.
* Descisions on code structure and frameworks is also up to you.

	
## Choose Your Own Adventure (Bonus)

At IZEA, we all have different skills, areas of interest, and expertese. We believe this makes us a better engineering organization. The following are a set of optional bonus specializations that you can add to your submission.

### The Experience Crafter

* Create an `Ember.js` front end for the admistrative component of the service (creation of links, etc).

### The Operator

* A major retailer has decided to use your service for a large promotional campaign. It will have to handle thousands of requests per second. How are you going to handle this volume?

### The Data Engineer

* You have been tasked with creating clicks stream analytics for the traffic coming through your service. How would you set this up? 

### The Cryptographer

* You have been given the additional requirement that your `tiny_url` sequence should be such that, given any `tiny_url`, an attacker couldn't (trivially) predict what the next `tiny_url` would be.
* An ideal solution would require **O(1)** storage, and **O(1)** compute.

	
