# kafka-with-docker
running docker with kafka

basic scripts to learn kafka using docker containers

Nov 2020
- windows fix for reading/writting to external files using volumes
1. update docker app settings "Resources" > "File Sharing" = explicity add the root folder you are wirting too
2. in RUN and compose fully qualify the path i.e d://path..
3. add the environment variable - COMPOSE_CONVERT_WINDOWS_PATHS=false
