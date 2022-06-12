### Find Duplicate Values: .duplicated() method
* To find duplicate values in the whole DataFrame
```python
DataFrame.duplicated()
```

* To find duplicate values in a specific column
```python
DataFrame['column-name'].duplicated()
```

### Delete Duplicate Values: .drop_duplicates() method
* To delete whole rows that contain *any* duplicate values found in another row in a pd DataFrame: 
```python
DataFrame.drop_duplicates()
```

* To delete duplicates found in a *specific column*  in a pd DataFrame:
```python
DataFrame.drop_duplicates(subset=['column-name'])
```
