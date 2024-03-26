# Obtain imagedocker 
pull docker.io/gnuoctave/octave:6.2.0

# Start container (command-line interface)
docker run -it --rm gnuoctave/octave:6.2.0 octave

# Start container GUI (experimental)
docker run \  --rm \  --network=host \  --env="DISPLAY" \  --volume="$HOME/.Xauthority:/root/.Xauthority:rw" \  gnuoctave/octave:6.2.0 \  octave --gui
