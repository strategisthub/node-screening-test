### Hotels Search End Point:
Create a BackEnd server using NodeJS/ExpressJS for creating Restful APIs for hotels.


APIs to create for hotels:
Create
Update
Edit
Delete
FindOne
findAll


findAll should be implemented in following way:
```
GET /hotels/find
```

### Query Params:
 
 * `name`: A part of hotel name matches using `.includes`
 * `city`: A city name that will use `Exact Match`.
 * `price`: A range of price like `100:500` or `1000:2000`. It uses a range filter.
 * `date`: A range of date as `10-12-2020:15-12-2020`. It uses a range filter.
 * `sort_field`: Field name to run sort against.
 * `sort_order`: Order of the sorting `asc/desc`


### Response: 

 ```
  {
    "hotels": [ //  Array of hotels]
  }
 ```
