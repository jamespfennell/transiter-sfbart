# Transiter / San Francisco BART


Installing the San Francisco BART
in a running Transiter instance is as simple as:

    curl -X PUT $TRANSITER_SERVER/systems/sfbart \
        -F 'config_file=https://raw.githubusercontent.com/jamespfennell/transiter-sfbart/master/Transiter-SF-BART-config.yaml'
        
    