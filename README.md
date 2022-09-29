# cdabsR_Session4_Practice
learning to connect to GitHub from R Studio Cloud and push changes

install.packages("usethis")
library(usethis)
use_git_config(user.name = "mattheweason", user.email = "matthew.eason@som.umaryland.edu")
git_sitrep()


# Create a personal access token

create_github_token()

# Add token to get credentials store
gitcreds::gitcreds

