# Lightweight python components example
This notebook demonstrates how to compile and execute the pipeline using simple python functions, also known as creating pipeline through lightweight. This notebook is originated from the kubeflow pipeline's [lighweight-component](https://github.com/kubeflow/pipelines/tree/master/samples/core/lightweight_component) example that is running on Kubeflow 0.7. We have modified this notebook to run with Kubeflow 1.x's user namespace separation with Tekton support.

This pipeline contains these steps, it creates `add` and `my_divmod` functions, converts to Kubeflow pipeline operation, defines the pipeline with hard coded parameters, and runs the pipeline on Tekton. You can see the detail about the pipeline at [Build Lightweight Python Components](https://www.kubeflow.org/docs/pipelines/sdk/lightweight-python-components/)

## Prerequisites
- Install [Kubeflow 1.0.2+](https://www.kubeflow.org/docs/started/getting-started/) and connect the cluster to the current shell with `kubectl`
- Install [kfp-tekton](/sdk/README.md#steps) SDK

## Instructions

Once you have completed all the prerequisites for this example, then you can start the Jupyter server in this directory and click on the `lightweight_component.ipynb` notebook. The notebook has step by step instructions for running the KFP Tekton pipeline.
```
jupyter notebook
```

## Acknowledgements

Thanks [Jiaxiao Zheng](https://github.com/numerology) for creating the original Lightweight_component notebook.
