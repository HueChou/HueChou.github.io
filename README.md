
# How to select specific type columns
```markdown
train.select_dtypes(np.int64)

for i, col in enumerate(train.select_dtypes('float')):
    
```
