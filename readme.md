## Deriv Academy CMS migration

### Requierments

Docker : Please intall docker based on [this document](https://docs.docker.com/engine/install/) first.

Git : You must have git for cloning the project.

### How To Run The Project

1. Clone the project.
2. cd into the root directory by running `cd decouple-academy`.
3. execute the following command to run the containers.

`docker compose up`

### Note:

you have to get two files .env.production and .env.developments from deriv-com TLs to be able to run the project.

### Note:

This is just a Proof of concept project and the workflow is not very practical and there are lots of things to consider. the purpose of this project is to provide vission on what we need to achieve for deriv-com + academy.

### Note:

Wordpress has been choosen for just demonestration and the academy team ( dev and content ) may wish to change it and use some other CMS. Please contact Prince Coaching for more info on this.

### Note:

if you faced with permissions issue on runing docker containers ( docker compose ) please check [this](https://stackoverflow.com/questions/48957195/how-to-fix-docker-got-permission-denied-issue) out.
