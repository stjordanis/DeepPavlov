# Pilot - Deeppavlov
An open source library for
 * building complicated natural language processing pipelines
 * training and infering natural language processing algorithms

## Installation
1. Create a virtual environment with `Python 3.6`
2. Activate the environment.
3. `cd` to the project root.
4. `pip install -r requirements.txt`

## Usage
```
python deep.py <mode> <path_to_config>
```
* `<mode>` can be 'train' or 'interact'
* `<path_to_config>` should be a path to an NLP pipeline json config

Available configs are:

*skills/hcn_new/config.json*

*models/classifiers/intents/config.json*

*models/ner/config.json*

*models/spellers/error_model/config_en.json*
