My-stub-alpine size is 115mb
My-stub:latest size is 238mb

The former is smaller than the latter because Alpine Linux is a specialized distro for Docker - it removes all the stuff not needed for running Docker containers, resulting in the 50% smaller size in disk usage AND content size.