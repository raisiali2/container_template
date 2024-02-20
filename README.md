# container_template

## .env file in container

### Active Parameters
The active parameters define paths and proxy settings that the application can use:

#### INPUT="./in": Sets the INPUT environment variable to specify the directory path (relative to the current working directory) where input files are located.

#### OUTPUT="./out": Sets the OUTPUT environment variable to specify the directory path (relative to the current working directory) where output files should be saved.

#### WEIGHTS="./weights": Sets the WEIGHTS environment variable to specify the directory path (relative to the current working directory) where model weights or similar data files are stored.

#### CFG="./cfg": Sets the CFG environment variable to specify the directory path (relative to the current working directory) for configuration files.

#### HTTP_PROXY="$http_proxy": Sets the HTTP_PROXY environment variable to the value of the http_proxy environment variable that is already set in the system. This is used to configure the application to use an HTTP proxy for internet connections.

#### HTTPS_PROXY="$https_proxy": Similarly, sets the HTTPS_PROXY environment variable to the value of the https_proxy environment variable. This is used for HTTPS connections through a proxy.

