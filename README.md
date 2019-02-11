# React app deployed to AWS using Docker and TravisCI

The purpose of this app is to learn and work with Docker and TravisCI for deploying apps to AWS using containerization and a continuous integration workflow.

See the /Notes folder for a rundown of the different processes and some self made documentation I've created which you may find helpful if you're learning about containerization and CI workflows as well.

### App Notes, Tools used and Setup:
- Docker CLI for container creation and management
- create-react-app
- Dockerfiles for production and development
- Using Docker with docker-compose and docker-compose.yaml configuration
- Setting up multi-phase build processes using Nginx for serving files
- Integrating GitHub and Travis CI for automatic testing and deployment to AWS Elastic Beanstalk
  - Generating API keys for AWS through an IAM user for the app
  - Creating environment secrets on Travis CI for accessing API keys
  - Exposing container ports on Elastic Beanstalk
