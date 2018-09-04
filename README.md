
# markdown
```markdown
df = pd.read_csv('../input/sample_submission.csv')
for i in np.arange(1,5):
    df['Target'] = i
    df.to_csv('sample_{}.csv'.format(i), index = False)
    
```
