# Kaiju metagenomics classifier for Sunbeam

## Installation:

With your sunbeam conda environment activated,

1. Clone into your Sunbeam directory:
    ```shell
    git clone https://github.com/sunbeam-labs/sbx_kaiju sunbeam/extensions/sbx_kaiju
    ```
    
2. Install the requirements:
    ```shell
    conda install --file sunbeam/extensions/sbx_kaiju/requirements.txt
    ```

3. Add the new config options to your config file:
    ```shell
    cat sunbeam/extensions/sbx_kaiju/config.yml >> my_config.yml
    ```

## Usage

This adds a new rule, `all_kaiju`. Specify this as your target to use Kaiju to classify your decontaminated samples.
