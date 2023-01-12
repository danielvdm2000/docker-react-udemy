# Build
docker build -f Dockerfile.dev -t danielvdm/frontend .

# Run
docker run -it -p 3000:3000 -v /home/node/app/node_modules -v ~/frontend:/home/node/app danielvdm/frontend