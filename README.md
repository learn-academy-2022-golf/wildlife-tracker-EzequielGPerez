Set up I followed this; 

### Create New Rails App
rails new rails-api -d postgresql -T
cd rails-api
rails db:create

### Setup git:
git remote add origin https://github.com/learn-academy-2022-golf/wildlife-tracker-elysemontano.git
git branch -M main
git status
git add .
 git status
git commit -m "initial commit"
git push origin main
git checkout -b setup

### Add Rspec
bundle add rspec-rails
rails generate rspec:install

For first story;
I made an animal table
added 2 animals a lion and an orca following their scientific binomial 
Then I updated Orca to orca
Then deleted orca

For second story;
Make a new branch sighting-crud-actions
I made it so I can add a sighting 
Also need to be able to update that sighting 
And I was able to remove an animal sighting
So pretty much the same for the first one

