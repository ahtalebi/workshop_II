# How to run
- Make sure Docker is installed and working on your system
- Clone the repository: `git clone git@github.com:ahtalebi/workshop_II.git`
- Build the Docker image using `docker build -t inference_insurance .`
- Run the Docker container (and mount a volume) using `docker run --rm --name infer_container -v /path/to/shared_folder:/home/dvisual/shared_folder/:rw inference_insurance`
- Check the contents of `shared_folder` for the output.
