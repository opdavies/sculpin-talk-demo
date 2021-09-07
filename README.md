# sculpin-talk-demo

    docker run --rm -it \
        -p 8000:8000 \
        -v $(pwd):/app \
        --name sculpin-demo \
        opdavies/sculpin-serve
