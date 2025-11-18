sudo apt-get update
sudo apt-get install -y build-essential libgeos-dev


uv run jupyter lab --ip 0.0.0.0 --port 8888 --no-browser
