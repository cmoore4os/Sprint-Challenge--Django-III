# Django Retrospective

__Subject: Djorg App__

Djorg is a personal organizional management(POM) application written in Python 3 using the Django framework for the backend(BE) and Javascript using the React library on the frontend(FE).

Although Djorg is a functioning application, currently it is meant to be a tutorial application of some basic ways to use Django with React. Current apps:

- Bookmarks - stores bookmarks - Django BE and Django FE
  - Models: Bookmark(id,url,name, notes, created_at, last_modified),Tag(id,name)
  
- Notes - stores notes -Django BE and React FE on separate repos
  - Models: Note(id, title,content,created_at,last_modified,user)
  
- Contacts - stores contacts - Django BE and React FE on the same repo
  - Models: (id, prefix_name,first_name,middle_name,last_name, suffix_name, phone,email, address, note,created_at,last_modified,user)
---
__Heroku__:
- The BE for all apps and the FE for all apps except Notes: https://djorg-pim.herokuapp.com/
- Notes FE https://djorg-pim-client.herokuapp.com/

__GitHub__:
- The BE for all apps and the FE for all apps except Notes: https://github.com/cmoore4os/djorg
- Notes FE: https://github.com/cmoore4os/djorg-client
___

__Status__: Beta - Djorg is as basic as it can get. The apps work and are deployed,but site navigation is almost nonexistant and it has no beauty to the styling. Users can sign-up and sign-in using Github Auth. Bootstrap is used for css. No other features have been added
___

__ToDo__: 
- Write the tutorial on how to implement the apps using the different Django/React combinations
- Fix navigations
- Beautify it; Remove Bootstrap
- Add a Project app
- write version of the Djorg where all of its apps use the Django BE and Django FE on same repos 
- write version of the Djorg where all of its apps use the Django BE and React FE on seperate repos
- write version of the Djorg where all of its apps use the Django BE and React FE on same repos

 



