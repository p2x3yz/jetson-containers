# pytorch

> [`CONTAINERS`](#user-content-containers) [`IMAGES`](#user-content-images) [`RUN`](#user-content-run) [`BUILD`](#user-content-build)

Containers for PyTorch with CUDA support.
Note that the [`l4t-pytorch`](/packages/l4t/l4t-pytorch) containers also include PyTorch, torchvision, and torchaudio.

<details open>
<summary><b><a id="containers">CONTAINERS</a></b></summary>
<br>

| **`pytorch:2.1`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:2.1` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-21_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-21_jp51.yml?label=pytorch-21:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-21_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:2.1-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-07, 5.4GB)`<br>[`dustynv/pytorch:2.1-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 5.4GB)`<br>[`dustynv/pytorch:2.1-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.4GB)` |

| **`pytorch:2.0`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:2.0` `pytorch` `torch` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-20_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-20_jp51.yml?label=pytorch-20:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-20_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dependants | [`auto_gptq`](/packages/llm/auto_gptq) [`awq`](/packages/llm/awq) [`awq:dev`](/packages/llm/awq) [`bitsandbytes`](/packages/llm/bitsandbytes) [`exllama`](/packages/llm/exllama) [`exllama:v2`](/packages/llm/exllama) [`faiss:lite`](/packages/vectordb/faiss_lite) [`gptq-for-llama`](/packages/llm/gptq-for-llama) [`l4t-diffusion`](/packages/l4t/l4t-diffusion) [`l4t-ml`](/packages/l4t/l4t-ml) [`l4t-pytorch`](/packages/l4t/l4t-pytorch) [`l4t-text-generation`](/packages/l4t/l4t-text-generation) [`langchain`](/packages/llm/langchain) [`langchain:samples`](/packages/llm/langchain) [`llava`](/packages/llm/llava) [`local_llm`](/packages/llm/local_llm) [`minigpt4`](/packages/llm/minigpt4) [`mlc`](/packages/llm/mlc) [`mlc:dev`](/packages/llm/mlc) [`nanodb`](/packages/vectordb/nanodb) [`nanosam`](/packages/vit/nanosam) [`nemo`](/packages/nemo) [`optimum`](/packages/llm/optimum) [`raft`](/packages/rapids/raft) [`sam`](/packages/vit/sam) [`stable-diffusion`](/packages/diffusion/stable-diffusion) [`stable-diffusion-webui`](/packages/diffusion/stable-diffusion-webui) [`tam`](/packages/vit/tam) [`text-generation-inference`](/packages/llm/text-generation-inference) [`text-generation-webui`](/packages/llm/text-generation-webui) [`torch2trt`](/packages/pytorch/torch2trt) [`torch_tensorrt`](/packages/pytorch/torch_tensorrt) [`torchaudio`](/packages/pytorch/torchaudio) [`torchvision`](/packages/pytorch/torchvision) [`transformers`](/packages/llm/transformers) [`transformers:git`](/packages/llm/transformers) [`transformers:nvgpt`](/packages/llm/transformers) [`tvm`](/packages/tvm) [`xformers`](/packages/llm/xformers) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:2.0-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 5.4GB)`<br>[`dustynv/pytorch:2.0-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-07, 5.4GB)`<br>[`dustynv/pytorch:2.0-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.4GB)` |

| **`pytorch:1.13`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:1.13` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-113_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-113_jp51.yml?label=pytorch-113:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-113_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:1.13-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.5GB)`<br>[`dustynv/pytorch:1.13-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 5.5GB)`<br>[`dustynv/pytorch:1.13-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.5GB)` |

| **`pytorch:1.12`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:1.12` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-112_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-112_jp51.yml?label=pytorch-112:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-112_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:1.12-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 5.5GB)`<br>[`dustynv/pytorch:1.12-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.5GB)`<br>[`dustynv/pytorch:1.12-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.5GB)` |

| **`pytorch:1.11`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:1.11` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-111_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-111_jp51.yml?label=pytorch-111:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-111_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:1.11-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 5.4GB)`<br>[`dustynv/pytorch:1.11-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.4GB)`<br>[`dustynv/pytorch:1.11-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-08-29, 5.4GB)` |

| **`pytorch:1.10`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:1.10` `pytorch` `torch` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-110_jp46`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-110_jp46.yml?label=pytorch-110:jp46)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-110_jp46.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T ==32.*` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:1.10-r32.7.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 1.1GB)` |

| **`pytorch:1.9`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch:1.9` |
| &nbsp;&nbsp;&nbsp;Builds | [![`pytorch-19_jp46`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/pytorch-19_jp46.yml?label=pytorch-19:jp46)](https://github.com/dusty-nv/jetson-containers/actions/workflows/pytorch-19_jp46.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T ==32.*` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/pytorch:1.9-r32.7.1`](https://hub.docker.com/r/dustynv/pytorch/tags) `(2023-09-24, 1.0GB)` |

| **`pytorch:2.0_use_distributed`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Aliases | `torch` |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=32.6` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`numpy`](/packages/numpy) [`cmake`](/packages/cmake/cmake_pip) [`onnx`](/packages/onnx) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile.2.0_use_distributed`](Dockerfile.2.0_use_distributed) |

</details>

<details open>
<summary><b><a id="images">CONTAINER IMAGES</a></b></summary>
<br>

| Repository/Tag | Date | Arch | Size |
| :-- | :--: | :--: | :--: |
| &nbsp;&nbsp;[`dustynv/pytorch:1.10-r32.7.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `1.1GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.11-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.11-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.11-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.12-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.12-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.12-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.13-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.13-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.13-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.5GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:1.9-r32.7.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `1.0GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.0-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.0-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-07` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.0-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.1-r35.2.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-07` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.1-r35.3.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-09-24` | `arm64` | `5.4GB` |
| &nbsp;&nbsp;[`dustynv/pytorch:2.1-r35.4.1`](https://hub.docker.com/r/dustynv/pytorch/tags) | `2023-08-29` | `arm64` | `5.4GB` |

> <sub>Container images are compatible with other minor versions of JetPack/L4T:</sub><br>
> <sub>&nbsp;&nbsp;&nbsp;&nbsp;• L4T R32.7 containers can run on other versions of L4T R32.7 (JetPack 4.6+)</sub><br>
> <sub>&nbsp;&nbsp;&nbsp;&nbsp;• L4T R35.x containers can run on other versions of L4T R35.x (JetPack 5.1+)</sub><br>
</details>

<details open>
<summary><b><a id="run">RUN CONTAINER</a></b></summary>
<br>

To start the container, you can use the [`run.sh`](/docs/run.md)/[`autotag`](/docs/run.md#autotag) helpers or manually put together a [`docker run`](https://docs.docker.com/engine/reference/commandline/run/) command:
```bash
# automatically pull or build a compatible container image
./run.sh $(./autotag pytorch)

# or explicitly specify one of the container images above
./run.sh dustynv/pytorch:2.1-r35.3.1

# or if using 'docker run' (specify image and mounts/ect)
sudo docker run --runtime nvidia -it --rm --network=host dustynv/pytorch:2.1-r35.3.1
```
> <sup>[`run.sh`](/docs/run.md) forwards arguments to [`docker run`](https://docs.docker.com/engine/reference/commandline/run/) with some defaults added (like `--runtime nvidia`, mounts a `/data` cache, and detects devices)</sup><br>
> <sup>[`autotag`](/docs/run.md#autotag) finds a container image that's compatible with your version of JetPack/L4T - either locally, pulled from a registry, or by building it.</sup>

To mount your own directories into the container, use the [`-v`](https://docs.docker.com/engine/reference/commandline/run/#volume) or [`--volume`](https://docs.docker.com/engine/reference/commandline/run/#volume) flags:
```bash
./run.sh -v /path/on/host:/path/in/container $(./autotag pytorch)
```
To launch the container running a command, as opposed to an interactive shell:
```bash
./run.sh $(./autotag pytorch) my_app --abc xyz
```
You can pass any options to [`run.sh`](/docs/run.md) that you would to [`docker run`](https://docs.docker.com/engine/reference/commandline/run/), and it'll print out the full command that it constructs before executing it.
</details>
<details open>
<summary><b><a id="build">BUILD CONTAINER</b></summary>
<br>

If you use [`autotag`](/docs/run.md#autotag) as shown above, it'll ask to build the container for you if needed.  To manually build it, first do the [system setup](/docs/setup.md), then run:
```bash
./build.sh pytorch
```
The dependencies from above will be built into the container, and it'll be tested during.  See [`./build.sh --help`](/jetson_containers/build.py) for build options.
</details>
