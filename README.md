__Archived: Not actively maintained anymore!__

# JitsiMeet
Jitsi Meet Video-Conference and Video-Call Docker Containers

## Still in Alpha-State, don't use yet!

## What is this?

This adds a Jisti-Server to your PhilleConnect-Setup.

This container can also be run sand-alone, without the rest of PhilleConnect. We then recommend to use the [official docker-jitsi-meet-container](https://github.com/jitsi/docker-jitsi-meet) though, since this is a fork from that for the reduced needs in the school-environment.

## How to run this

To run this:

- clone this repo
- copy the `settings.env.default` to `settings.env`: `cp settings.env.default settings.env`
- run the `./gen-passwords` to create random passwords in it
- edit the first section of your `settings.env` according to your setup
- run `docker-compose up -d`
