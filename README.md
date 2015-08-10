# geodata
Geospatial data and cluster analysis tutorial

### Local installation

```bash
# Clone the repo
> git clone https://github.com/luciasantamaria/geodata.git
> cd geodata/tutorial/

# Create a virtual  environment, install virtualenv if needed
> pip install virtualenv
> virtualenv -p python3.4 .env

# Activate virtualenv by sourcing its activation scripts
> source .env/bin/activate
> . .env/bin/activate.fish  # for fish users out there

# Install the project dependencies using pip3.X
> pip3.4 install -r requirements.txt

```

### Start Jupyter notebook

```bash
> ipython notebook

```

### Start local web server

```bash
> python -m SimpleHTTPServer 8000

```
Files will be served at localhost:8000
