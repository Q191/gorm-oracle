## Username "c##oracle" escaped as "c%23%23oracle"

```
DB, err = gorm.Open(oracle.Open("oracle://c%23%23oracle:oracle@127.0.0.1:1521/xe"), &gorm.Config{})
if err != nil {
	panic("failed to connect database")
}
```
