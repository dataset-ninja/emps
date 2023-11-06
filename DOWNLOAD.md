Dataset **EMPS** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/9/9/GM/B9JURbsqv1dYvFL2kGjetiorEty8xLmwbFhOSf26ovWkZfhcrD7XH4bJoAHpBsvwjSOt5DQkPv2bk3lxbOXbu9c6UC4MFuAPXwA5IfaiUQlKjBVG9cxWGXZvqHSs.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='EMPS', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

