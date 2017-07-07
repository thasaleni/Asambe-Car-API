# Asambe Car Make and Model API

Autocomplete Search of Car models and Makes


### Prerequisites

Example Makes query

```
http://{server}:8080/asambe/carApi?type=MAKE&token=&make=a
```
Example Result 
```
{
  "cars" : {
    "makes" : {
      "APRILIA" : {
        "id" : 5,
        "name" : "APRILIA"
      },
      "ASTON MARTIN" : {
        "id" : 4,
        "name" : "ASTON MARTIN"
      },
      "ALFA ROMEO" : {
        "id" : 2,
        "name" : "ALFA ROMEO"
      },
      "ARGO" : {
        "id" : 126,
        "name" : "ARGO"
      },
      "AUDI" : {
        "id" : 7,
        "name" : "AUDI"
      },
      "ARCTIC CAT" : {
        "id" : 6,
        "name" : "ARCTIC CAT"
      },
      "AM GENERAL" : {
        "id" : 121,
        "name" : "AM GENERAL"
      },
      "ACURA" : {
        "id" : 1,
        "name" : "ACURA"
      },
      "AVANTI" : {
        "id" : 9,
        "name" : "AVANTI"
      },
      "AMERICAN IRONHORSE" : {
        "id" : 3,
        "name" : "AMERICAN IRONHORSE"
      },
      "ATK" : {
        "id" : 111,
        "name" : "ATK"
      },
      "AMERICAN LAFRANCE" : {
        "id" : 134,
        "name" : "AMERICAN LAFRANCE"
      },
      "AUTOCAR LLC." : {
        "id" : 8,
        "name" : "AUTOCAR LLC."
      }
    }
  }
}
```
Example Model Query

```
http://{server}:8080/asambe/carApi?type=MODEL&token=&make=BMW&model=x
```
Example Result
```
{
  "cars" : {
    "models" : {
      "X1" : {
        "id" : 11656,
        "name" : "X1",
        "makeYear" : {
          "id" : 546,
          "year" : 2010,
          "make" : {
            "id" : 12,
            "name" : "BMW"
          }
        }
      },
      "X3" : {
        "id" : 2474,
        "name" : "X3",
        "makeYear" : {
          "id" : 1302,
          "year" : 2013,
          "make" : {
            "id" : 12,
            "name" : "BMW"
          }
        }
      },
      "X4" : {
        "id" : 4452,
        "name" : "X4",
        "makeYear" : {
          "id" : 1160,
          "year" : 2015,
          "make" : {
            "id" : 12,
            "name" : "BMW"
          }
        }
      },
      "X5" : {
        "id" : 2475,
        "name" : "X5",
        "makeYear" : {
          "id" : 1302,
          "year" : 2013,
          "make" : {
            "id" : 12,
            "name" : "BMW"
          }
        }
      },
      "X6" : {
        "id" : 1306,
        "name" : "X6",
        "makeYear" : {
          "id" : 1387,
          "year" : 2012,
          "make" : {
            "id" : 12,
            "name" : "BMW"
          }
        }
      }
    }
  }
}
```
## Built With

* [Spring Boot](https://projects.spring.io/spring-boot/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [MySQL](https://www.mysql.com/) - Used for data storage

## Contributing



## Authors

* **Phumzile Saleni** - *Initial work* - [Phumzile]https://github.com/thasaleni)



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Uses [Artukao's Vehicle Make Model](https://github.com/arthurkao/vehicle-make-model-data/blob/master/mysql_data.sql)

