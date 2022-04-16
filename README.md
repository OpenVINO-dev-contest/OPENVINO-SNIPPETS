# OpenVINO Snippets for VScode

This extension includes a set of useful code snippets for developing OpenVINO.All the snippets starts with "ov", so typing a letter ov gives recommendation for all the available OpenVINO snippets.

## Features

The extension snippets sets includes:

- `ov:example`: Sample Code for model deployment workflow.
- `ov:init`: Create OpenVINO™ Runtime Core".
- `ov:device`: Show available_devices in your computer.
- `ov:compile`: Reading and Loading a Model.
- `ov:inputinfo`: Get model input information.
- `ov:outputinfo`: Get model output information.
- `ov:input`: Prepare input data (cpp).
- `ov:output`: Process output data (cpp).
- `ov:request`: Create an Inference Request
- `ov:infer`: Do inference synchronously.
- `ov:ppp`: Integrate Preprocessing steps into execution graph.
- `ov:reshape`: Change model input shape.
- `ov:dynamic`: Configure the dynamic input shape.
- `ov:queue`: Create infer request queue.
- `ov:caching`: create a model_cache directory as a subdirectory of model, where the model will be cached for the specified device.

## Installation
<a name="installation"></a>

Install Visual Studio Code from [here](https://code.visualstudio.com/).
Install this extension by selecting `Install Extension` in the command pallette (cmd-shift-x) and searching for "OpenVINO Snippets".

The generated code also relies on the following python dependencies:
```bash
1. Python runtime: pip install openvino
2. C++ runtime: [Download Page](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/download.html)