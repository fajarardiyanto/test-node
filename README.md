# Rest Api Generator

**rest-api-generator** generates standard structure rest api application using module [flt-go-router](https://github.com/fajarardiyanto/flt-go-router).

## Getting started

### Flags
|  flag   |                     description                     |
|:-------:|:---------------------------------------------------:|
|   pkg   | name package (example: github.com/testing/pkg-name) |
| appName |      name application (example: testing-name)       |
| modules |           embed modules (example: mysql)            |

### Modules Register
| Name  |
|:-----:|
| mysql |
| redis |

### Usage
```shell
./rest-api-generator --pkg testing --appName testing-name --modules mysql,redis
```

```shell
cd testing && make run
```

or see Makefile