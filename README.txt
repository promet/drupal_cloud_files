Installation

- Download and install the Libraries (7.x-2.x branch) module
  http://drupal.org/project/libraries

- Download the PHP SDK for OpenStack/Rackspace APIs (http://php-opencloud.com/)
  and place it in sites/all/libraries/php-opencloud/ so that the path to
  php-opencloud.php is sites/all/libraries/php-opencloud/lib/php-opencloud.php

- Configure your setttings at /admin/config/media/cloud-files

- Visit admin/config/media/file-system and set the Default download method to
  Rackspace Cloud Files

- Add a field of type File or Image etc and set the Upload destination to
  Rackspace Cloud Files in the Field Settings tab.