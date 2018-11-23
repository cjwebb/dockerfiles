# Quickstart

This docker container runs [Elm-live](https://github.com/wking-io/elm-live).

Example usage:

   docker run -it --rm -v "$(pwd):/code" -w "/code" -e "HOME=/tmp" -u $UID:$GID -p 8000:8000 cjwebb/elm-live src/Main.elm -h 127.0.0.1 --pushstate -- --output=elm.js

