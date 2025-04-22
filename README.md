# educause
This is a sample Web Application that features node, python, postgres, and nginx. 

## Building the Simple Web Application

### Original
docker compose up -d --build

### Chainguard Version
docker compose -f docker-compose-chainguard.yaml up -d --build

### Verify the Output
Check the website at `localhost` and the API at `localhost:5000/courses`

## Find CVEs for the Images
Review the CVEs associated with each using your favorite scanner. 
E.g., `grype educause-frontend` and `grype educause-frontend-cg`