# MalaysiaHoliday
To get all holidays dates in Malaysia


### Usage

Holidays in current years

`Holiday::init()->getAllRegionHoliday()->get();`

Holidays in specific years

`Holiday::init()->getAllRegionHoliday("2017")->get();`

Holidays by regional

`Holiday::init()->getRegionHoliday("Selangor")->get();`

Holidays by regional in 2017

`Holiday::init()->getRegionHoliday("Selangor","2017")->get();`


Grouping and Filter result
`Holiday::init()->getAllRegionHoliday()->groupByMonth()->get();`
`Holiday::init()->getAllRegionHoliday()->filterByMonth("January")->get();  //date('F')	`


### Source
- http://www.officeholidays.com/countries/malaysia

### MIT Licience