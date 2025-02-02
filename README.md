# CPP Demo
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ffossas%2Fcpp-vsi-demo.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ffossas%2Fcpp-vsi-demo?ref=badge_shield)


This project demonstrates the minimal functionality for FOSSA C/C++ support via VSI and IAT.

# How to run

1. Clone this project locally.
1. Install the [fossa CLI](https://github.com/fossas/fossa-cli/releases) somewhere in your `$PATH`.
1. Follow along in `scripts.sh`- the comments describe the demo flow. Fill in the placeholders (denoted by `<` and `>`) for the commands when running them.

Make sure to run the "regenerate binaries" steps; in order to keep demo's consistent we no longer vendor binaries in this project.

# Directory overview

* `bin` - Contains binaries to link with projects. These binaries aren't real binaries; they're just random files.
* `internal-json-parser` - An example internal library. Contains the `bin/jq/jq.o` binary.
* `example-internal-project` - An example internal project. Contains vendored source (in `vendor`), and the `bin/libauth_internal` and `bin/libjson_internal` binaries (in `include`).

All other files not mentioned here (eg `.c` and `.h` files) are placeholders.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ffossas%2Fcpp-vsi-demo.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ffossas%2Fcpp-vsi-demo?ref=badge_large)