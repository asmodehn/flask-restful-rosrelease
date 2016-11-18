## flask_restful (indigo) - 0.3.4-1

The packages in the `flask_restful` repository were released into the `indigo` distro by running `/usr/bin/bloom-release --rosdistro indigo --track indigo flask_restful` on `Fri, 18 Nov 2016 05:02:35 -0000`

The `flask_restful` package was released.

Version of package(s) in repository `flask_restful`:

- upstream repository: https://github.com/flask-restful/flask-restful.git
- release repository: unknown
- rosdistro version: `null`
- old version: `0.3.4-0`
- new version: `0.3.4-1`

Versions of tools used:

- bloom version: `0.5.23`
- catkin_pkg version: `0.2.10`
- rosdep version: `0.11.5`
- rosdistro version: `0.5.0`
- vcstools version: `0.1.39`


## flask_restful (indigo) - 0.3.4-0

The packages in the `flask_restful` repository were released into the `indigo` distro by running `/usr/bin/bloom-release --rosdistro indigo --track indigo flask_restful` on `Wed, 16 Nov 2016 06:14:37 -0000`

The `flask_restful` package was released.

Version of package(s) in repository `flask_restful`:

- upstream repository: https://github.com/flask-restful/flask-restful.git
- release repository: unknown
- rosdistro version: `null`
- old version: `null`
- new version: `0.3.4-0`

Versions of tools used:

- bloom version: `0.5.23`
- catkin_pkg version: `0.2.10`
- rosdep version: `0.11.5`
- rosdistro version: `0.5.0`
- vcstools version: `0.1.39`


# flask-restful-rosrelease
Releasing https://github.com/flask-restful/flask-restful on ROS

| Indigo | Jade |
|:------:|:----:|
| [![Build Status](https://travis-ci.org/asmodehn/flask-restful-rosrelease.svg?branch=release%2Findigo%2Fflask_restful)](https://travis-ci.org/asmodehn/flask-restful-rosrelease)| [![Build Status](https://travis-ci.org/asmodehn/flask-restful-rosrelease.svg?branch=release%2Fjade%2Fflask_restful)](https://travis-ci.org/asmodehn/flask-restful-rosrelease) |

    test_accept_no_default_match_q0_not_acceptable(self):
    """
    q=0 should be considered NotAcceptable,
    but this depends on werkzeug >= 1.0 which is not yet released
    so this test is expected to fail until we depend on werkzeug >= 1.0
    """
