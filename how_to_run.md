# How to run

## Inference

1. Put the pertained model into `pretrained` directory

    ```shell
    mkdir pretrained
    mv hovernet_fast_pannuke_type_tf2pytorch.tar pretrained/
    ```

2. Put the input images into `dataset` directory

	```shell
	mkdir -p dataset/sample_tiles/imgs
	mkdir -p dataset/sample_tiles/pred
	mv input.jpg dataset/sample_tiles/imgs/
	```

3. Run the inference code

	```shell
	./run_tile.sh
	```

## Utilize the output

Open and run the `examples/usage.ipynb` file

