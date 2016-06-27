# php-daterange

Php date range implementation, usualy used in PgSQL database

```php
<?php

$dateRange = new Salamek\DateRange(\DateTimeInterface $startDate, \DateTimeInterface $endDate);

$dateRange->getStartDate(); //$startDate
$dateRange->getEndDate(); //$endDate
$datePeriod = $dateRange->datePeriod(\DateInterval $dateInterval); // same as \DatePeriod(\DateTimeInterface $startDate, \DateInterval $dateInterval, \DateTimeInterface $endDate)


```
