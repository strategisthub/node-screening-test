## Hotels Search End Point:
Create a BackEnd server using NodeJS/ExpressJS and MongoDB for creating Restful APIs for hotels.


### APIs to create for hotels:
* Create
* Update
* Edit
* Delete
* FindOne based on hote slug or id.
* findAll


### findAll API should accept following query paramters to apply as filters.

### Query Params:
 
 * `name`: A part of hotel name matches using `.includes`
 * `city`: A city name that will use `Exact Match`.
 * `price`: A range of price like `100:500` or `1000:2000`. It uses a range filter.
 * `date`: A range of date as `10-12-2020:15-12-2020`. It uses a range filter.
 * `sort_field`: Field name to run sort against.
 * `sort_order`: Order of the sorting `asc/desc`


### Expected Response find API:

 ```
  {
    "hotels": [ //  Array of hotels]
  }
 ```
