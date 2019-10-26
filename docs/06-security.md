
# Tips on Security

Blindly running other people's code is a dangerous proposition. Although students are unlikely to deliberately include malicious code such as `system("rm -rf /")`, a hacker who discovers an unsecured upload site for RMarkdown files could easily do this.

A student is more likely to include code such as `install.packages("tidyverse")` which will not only take a long time to run, but can seriously damage your R installation.

While it is not possible to have a setup that is 100% free from vulnerabilities, here are two tips that can minimize the chances of running problematic code.

## Controlling who can submit

### Use a Digital Learning Environment (DLE)

## Run code inside a virtual environment or container

