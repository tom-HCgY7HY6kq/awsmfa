# awsmfa
A helper tool to manage MFA for AWS CLI

## Prerequisites

 - AWS CLI
 - jq
 - (Optional) Bitwarden CLI

## Installation

 1. Clone the files to a directory such as /opt/.
 2. Symlink the binary to a directory on your path. E.g. `sudo ln -s /opt/awsmfa /usr/bin/awsmfa`

## Running

 1. Run `awsmfa configure` to get started with a new default profile. Or you can use `awsmfa configure --profile profile-name` to specify the profile.
 2. Run `awsmfa [TOTP CODE]` to authenticate with MFA