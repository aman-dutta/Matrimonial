INDEX /dogs            GET Display a list of all the dogs
NEW   /dogs/new        GET Dsiplay form to make a new dog
CREATE /dogs           POST  Add new dog to DB
SHOW   /digs/:id       GET  Shows info about one dog 
EDIT    /dogs/:id/edit GET  SHow edit form for one dog
UPDATE  /dogs/:id      PUT   Update particular dog, then redirect somewhere
Destroy  /dogs/:id     DELETE    Delete a particular dog, then redirect somewhere


INDEX   /cmapgrounds
NEW     /campgrounds/new
CREATE  /campgrounds
SHOW    /campgrounds/:id

NEW campgrounds/:id/comments/new    GET
CREATE cmapgrounds/:id/comments     POST