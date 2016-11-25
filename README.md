# packager.io-dockerhub-bridge

The webhooks on packager.io unfortunately dont work to trigger docker image builds on hub.docker.com.

Thsi script is a bridge / wrapper to achieve this goal anyway.

Just configure packager.io to access this script and the configured dockerhub webhook will trigger the build.
