## zoo.pipeline.api.torch package
### Load Torch Model


**Python example**
```python
model = Net.loadTorch("/tmp/torch_model") //load from local fs
model = Net.loadTorch("hdfs://...") //load from hdfs
model = Net.loadTorch("s3://...") //load from s3
```

