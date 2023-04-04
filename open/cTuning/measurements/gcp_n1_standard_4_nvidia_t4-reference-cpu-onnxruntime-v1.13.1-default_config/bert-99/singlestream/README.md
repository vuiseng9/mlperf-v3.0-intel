This experiment is generated using [MLCommons CM](https://github.com/mlcommons/ck). Please follow this [README](../../../../code/bert-99/README.md) for reproducing this result.

## CM Run Command
```
cm run script \
	--tags=generate-run-cmds,inference,_populate-readme,_all-scenarios \
	--model=bert-99 \
	--device=cpu \
	--implementation=reference \
	--backend=onnxruntime \
	--execution-mode=valid \
	--results_dir=/home/gfursin/inference_3.0_results \
	--quiet
```
## Dependent CM commands automatically generated by the above command


1.  `cm run script --tags=detect,os`


2.  `cm run script --tags=get,sys-utils-cm`


3.  `cm run script --tags=get,python`


4.  `cm run script --tags=get,mlcommons,inference,src,_deeplearningexamples`

## Dependent CM commands specific to the MLPerf inference implementation automatically generated by the above command


1. `cm run script --tags=detect,os`


2. `cm run script --tags=detect,cpu`


3. `cm run script --tags=get,sys-utils-cm`


4. `cm run script --tags=get,python`


5. `cm run script --tags=get,generic-python-lib,_onnxruntime`


6. `cm run script --tags=get,generic-python-lib,_torch`


7. `cm run script --tags=get,generic-python-lib,_transformers`


8. `cm run script --tags=get,ml-model,language-processing,bert-large,raw,_fp32,_onnx`


9. `cm run script --tags=get,dataset,squad,original`


10. `cm run script --tags=get,dataset-aux,squad-vocab`


11. `cm run script --tags=generate,user-conf,mlperf,inference`


12. `cm run script --tags=get,loadgen`


13. `cm run script --tags=get,mlcommons,inference,src,_deeplearningexamples`


14. `cm run script --tags=get,generic-python-lib,_tokenization`