# Shortcut for backend deployment
# git remote add deploy-backend https://github.com/hpoonawala28/instagram-clone-backend.git

# Shortcut for frontend deployment
# git remote add deploy-frontend https://github.com/hpoonawala28/instagram-clone-frontend.git

comit and push the code first on  root (instagram_clone)

 then push it to te back end sub tree(for backend folder)
      git subtree push --prefix backend deploy-backend main

 then push it to te front end sub tree(for frontend folder)
       git subtree push --prefix frontend deploy-frontend main


