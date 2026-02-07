# Shortcut for backend deployment
# git remote add deploy-backend https://github.com/hpoonawala28/instagram-clone-backend.git

# Shortcut for frontend deployment
# git remote add deploy-frontend https://github.com/hpoonawala28/instagram-clone-frontend.git


  git subtree push --prefix backend deploy-backend main

  git subtree push --prefix frontend deploy-frontend main