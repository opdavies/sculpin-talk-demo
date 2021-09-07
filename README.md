# sculpin-talk-demo

A demonstration [Sculpin](https://sculpin.io) website, generated from my [Sculpin Skeleton](https://github.com/opdavies/sculpin-skeleton) project.

## Running locally

The easiest way to run the site locally is by using my [Sculpin Serve docker image](https://github.com/opdavies/docker-image-sculpin-serve):

    docker run --rm -it \
        -p 8000:8000 \
        -v $(pwd):/app \
        --name sculpin-demo \
        opdavies/sculpin-serve

This will install the Composer dependencies, generate and serve the site at http://localhost:8000, and automatically re-generate the site if any changes are made.

## Links

* To see the generated site, go to <https://sculpin-talk-demo.netlify.app>.
* For more information, and to see the slides and video for the talk, go to <https://www.oliverdavies.uk/talks/building-static-websites-sculpin>.
