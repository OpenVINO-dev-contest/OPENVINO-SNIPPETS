# OpenVINO Snippets for VScode

This extension includes a set of useful code snippets for developing OpenVINO.All the snippets starts with "ov", so typing a letter ov gives recommendation for all the available OpenVINO snippets.

## Features

The extension snippets sets includes:

- `ov:import`: Import OpenVINO package.
- `ov:core`: Initialize Inference Engine with IECore().
- `ov:streams`: set throughput streams.
- `ov:device`: Show available_devices in your computer.
- `ov:loadnetwork`: Reading and Loading a Model.
- `ov:inputinfo`: Get model input information.
- `ov:outputinfo`: Get model output information.
- `ov:sync_infer`: Doing a sync inference.
- `ov:async_infer`: Doing async inference and waiting for the result is ready.
- `ov:reshape`: Change model input shape.
- `ov:batchsize`: set model's batch_size.
- `ov:caching`: create a model_cache directory as a subdirectory of model, where the model will be cached for the specified device.

## Installation
<a name="installation"></a>

Install Visual Studio Code from [here](https://code.visualstudio.com/).
Install this extension by selecting `Install Extension` in the command pallette (cmd-shift-x) and searching for "OpenVINO Snippets".

The generated code also relies on the following python dependencies:
```bash
pip install openvino
