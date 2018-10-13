## kolabspace/partkeepr docker image repository

This repository is based on the [`bluelotussoftware/partkeepr`][0]
[partkeepr][1] docker has been updated to use recent releases. It includes additional functionality:
* cron
* nano

> The most recent version is: 1.4.0

To use it, you need to have a working [docker][2] installation. Start by running
the following command:

    $ docker run -d -p 80:80 --name partkeepr kolabspace/partkeepr

Or to run it together with a MariaDB database container.

    $ docker-compose up

[0]: https://github.com/bluelotussoftware/partkeepr
[1]: http://www.partkeepr.org
[2]: https://www.docker.io
