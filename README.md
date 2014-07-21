CodeIgniter Mail Queue
=====================

General Information
-------------------

CI Mail Queue is a simple library (extended from CI_Mail) to queue emails in database and send them in background with CronJobs.

How to Use?
------------

Import the schema and add cronjobs.

E.g.:
- Send pending emails each 2 minutes.
 - */2 * * * * php /var/www/index.php queue_email/send_queue
- Send failed emails each 5 minutes.
 - */5 * * * * php /var/www/index.php queue_email/retry_queue

Enjoy!
