
## Links
* Link to master https://github.com/jbach197/14-relationship-modeling
* Link to pull request https://github.com/codefellows-seattle-javascript-401d24/14-relationship-modeling/compare/master...jbach197:lab14-jen?expand=1
* Link to Heroku https://bachlab-14.herokuapp.com/
* Link to Travis

## Configuration 

#### Feature Tasks
  * continue working on the `express` and `mongoDB` REST API that you started yesterday
  * include an additional resource that contains a "relationship" to the single resource that has already been created
  * create `GET`, `POST`, `PUT`, and `DELETE` routes for your newly added resource
  * test your application to ensure that it meets the standard criteria of a working **full CRUD** REST API
  * use `populate` in the `get()` route logic your  `/api/new-resource-name/:id` route to populate the associated property used to house related resources **(ex: `List.findById(req.params.id).populate('notes')`)**
