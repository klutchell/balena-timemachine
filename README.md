# balena-timemachine

Run a Samba server compatible with MacOS Time Machine

## Getting Started

You can one-click-deploy this project to balena using the button below:

[![deploy with balena](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/klutchell/balena-timemachine)

## Manual Deployment

Alternatively, deployment can be carried out by manually creating a [balenaCloud account](https://dashboard.balena-cloud.com) and application,
flashing a device, downloading the project and pushing it via the [balena CLI](https://github.com/balena-io/balena-cli).

## Usage

Once your device joins the fleet you'll need to allow some time for it to download the various services.

When it's done you should be able to discover the share at `smb://timemachine.local/TimeMachine`.

Documentation for the base image can be found at <https://hub.docker.com/r/mbentley/timemachine/>.

## Contributing

Please open an issue or submit a pull request with any features, fixes, or changes.
