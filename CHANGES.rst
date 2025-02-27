..
    This file is part of pytest-invenio.
    Copyright (C) 2018 CERN.

    pytest-invenio is free software; you can redistribute it and/or modify it
    under the terms of the MIT License; see LICENSE file for more details.

Changes
=======

Version 1.2.0 (released 2019-07-31)

- Adds fixture for creating default Location.
- Adds fixture for creating Bucket from directory with files.

Version 1.1.1 (released 2019-05-21)

- Adds pytest-cov as install dependency.

Version 1.1.0 (released 2019-02-15)

- Changes name of fixture from celery_config to celery_config_ext due to
  unreliable overwriting of celery_config fixture name.

Version 1.0.6 (released 2018-12-03)

- Fixes overwriting of celery_config fixture

Version 1.0.5 (released 2018-10-08)

- Adds default Content Security Policy header to the app configuration.
- Fixes issue with default tests scope.

Version 1.0.4 (released 2018-08-14)

- Bumps pytest minimun version to 3.8.0.

Version 1.0.3 (released 2018-09-05)

- Moves module dependent imports inside the fixture functions in order to
  decouple dependencies for Invenio apps or modules that might not be using
  them.

Version 1.0.2 (released 2018-05-25)

Version 1.0.1 (released 2018-04-17)

Version 1.0.0 (released 2018-03-22)
