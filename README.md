# DogsBreedsClassifier

<!-- To check GitHub Workflow Keep thing simple -->
<!-- max_epoch=5 and n_trails=2 -->

## WORKFLows
- [![TrainPipeline](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-train.yml/badge.svg)](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-train.yml)
- [![TestPipeline](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-eval.yml/badge.svg)](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-eval.yml)
- [![InferPipeline](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-infer.yml/badge.svg)](https://github.com/Muthukamalan/DogsBreedsClassifier/actions/workflows/ci-infer.yml)



## Inference

```log
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting load_image
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished load_image
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting infer
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished infer
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting save_prediction_image
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished save_prediction_image
<class 'omegaconf.listconfig.ListConfig'> "conv_ratio":         1.2
"depths":             [3, 3, 15, 3]
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting load_image
"dims":               [6, 12, 24, 36]
"head_fn":            default
"in_chans":           3
"lr":                 0.001
"min_lr":             1e-06
"model_name":         Mamba
"num_classes":        10
"pretrained":         False
"scheduler_factor":   0.1
"scheduler_patience": 5
"trainable":          False
"weight_decay":       1e-05
Processed guess2.jpg: Poodle (0.89)
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished load_image
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting infer
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished infer
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:22 - Starting save_prediction_image
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished save_prediction_image
Processed guess1.jpg: Boxer (0.96)
2024-11-10 20:22:17 | INFO     | utils.logging_utils:wrapper:25 - Finished main
```

- **collab**
    - @abhiya
    - @mhema
    - @muthu
