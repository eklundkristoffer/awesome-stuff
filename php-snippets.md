#### Interval to human readable format
> Credit: https://twitter.com/michaeldyrynda/status/1629702214917980166
```php
use Carbon\CarbonInterval;

CarbonInterval::seconds(108)
  ->cascade()
  ->forHumans(); // 1 minute 48 seconds
 
 CarbonInterval::minutes(108)
  ->cascade()
  ->forHumans(); // 1 hour 48 minutes
  
 CarbonInterval::hours(108)
  ->cascade()
  ->forHumans(); // 4 days 12 hours
```
