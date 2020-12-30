# General Info
A web app for communities to post suspicious activity (i.e. theft, shootings, etc) occurring in their neighborhood, so that others are aware of what to be more careful about. The web app is currently only focused on Chicago neighborhoods.


# Technologies Used
- Ruby on Rails
- React
- Postgresql
- CSS
- Bootstrap


# Setup
- Backend created with rails new and rails scaffold
- One database table containing all data
- Frontend built with React and styled with Bootstrap and CSS

# Problems
- Get input boxes to clear out after user submits a post
- Couldn't get gem 'chicago_crimes_one_year' to work


# Potential Improvements Later
- Add external API using a gem for Chicago crime data
- With more data, add a dropdown feature for filtering for specific Chicago neighborhoods
- Integrate longitude/latitude data that should be available in the gem mentioned above with Google Maps API to show location of crime/suspicious activity on a map
- Integrate a heat map to show which neighborhoods have high activity of postings occurring to give an idea to the user of potentially dangerous areas

# Link to Backend
https://github.com/chingmm/neighborhood_watch_backend
