# cudf

> [`CONTAINERS`](#user-content-containers) [`IMAGES`](#user-content-images) [`RUN`](#user-content-run) [`BUILD`](#user-content-build)

<details open>
<summary><b><a id="containers">CONTAINERS</a></b></summary>
<br>

| **`cudf`** | |
| :-- | :-- |
| &nbsp;&nbsp;&nbsp;Builds | [![`cudf_jp51`](https://img.shields.io/github/actions/workflow/status/dusty-nv/jetson-containers/cudf_jp51.yml?label=cudf:jp51)](https://github.com/dusty-nv/jetson-containers/actions/workflows/cudf_jp51.yml) |
| &nbsp;&nbsp;&nbsp;Requires | `L4T >=34.1.0` |
| &nbsp;&nbsp;&nbsp;Dependencies | [`build-essential`](/packages/build-essential) [`python`](/packages/python) [`cmake`](/packages/cmake/cmake_pip) [`numpy`](/packages/numpy) [`cupy`](/packages/cupy) [`numba`](/packages/numba) [`protobuf:apt`](/packages/protobuf/protobuf_apt) |
| &nbsp;&nbsp;&nbsp;Dependants | [`cuml`](/packages/rapids/cuml) |
| &nbsp;&nbsp;&nbsp;Dockerfile | [`Dockerfile`](Dockerfile) |
| &nbsp;&nbsp;&nbsp;Images | [`dustynv/cudf:r35.2.1`](https://hub.docker.com/r/dustynv/cudf/tags) `(2023-09-07, 6.4GB)`<br>[`dustynv/cudf:r35.3.1`](https://hub.docker.com/r/dustynv/cudf/tags) `(2023-08-29, 6.4GB)`<br>[`dustynv/cudf:r35.4.1`](https://hub.docker.com/r/dustynv/cudf/tags) `(2023-08-29, 6.4GB)` |
| &nbsp;&nbsp;&nbsp;Notes | installed under /usr/local |

</details>

<details open>
<summary><b><a id="images">CONTAINER IMAGES</a></b></summary>
<br>

| Repository/Tag | Date | Arch | Size |
| :-- | :--: | :--: | :--: |
| &nbsp;&nbsp;[`dustynv/cudf:r35.2.1`](https://hub.docker.com/r/dustynv/cudf/tags) | `2023-09-07` | `arm64` | `6.4GB` |
| &nbsp;&nbsp;[`dustynv/cudf:r35.3.1`](https://hub.docker.com/r/dustynv/cudf/tags) | `2023-08-29` | `arm64` | `6.4GB` |
| &nbsp;&nbsp;[`dustynv/cudf:r35.4.1`](https://hub.docker.com/r/dustynv/cudf/tags) | `2023-08-29` | `arm64` | `6.4GB` |

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
./run.sh $(./autotag cudf)

# or explicitly specify one of the container images above
./run.sh dustynv/cudf:r35.2.1

# or if using 'docker run' (specify image and mounts/ect)
sudo docker run --runtime nvidia -it --rm --network=host dustynv/cudf:r35.2.1
```
> <sup>[`run.sh`](/docs/run.md) forwards arguments to [`docker run`](https://docs.docker.com/engine/reference/commandline/run/) with some defaults added (like `--runtime nvidia`, mounts a `/data` cache, and detects devices)</sup><br>
> <sup>[`autotag`](/docs/run.md#autotag) finds a container image that's compatible with your version of JetPack/L4T - either locally, pulled from a registry, or by building it.</sup>

To mount your own directories into the container, use the [`-v`](https://docs.docker.com/engine/reference/commandline/run/#volume) or [`--volume`](https://docs.docker.com/engine/reference/commandline/run/#volume) flags:
```bash
./run.sh -v /path/on/host:/path/in/container $(./autotag cudf)
```
To launch the container running a command, as opposed to an interactive shell:
```bash
./run.sh $(./autotag cudf) my_app --abc xyz
```
You can pass any options to [`run.sh`](/docs/run.md) that you would to [`docker run`](https://docs.docker.com/engine/reference/commandline/run/), and it'll print out the full command that it constructs before executing it.
</details>
<details open>
<summary><b><a id="build">BUILD CONTAINER</b></summary>
<br>

If you use [`autotag`](/docs/run.md#autotag) as shown above, it'll ask to build the container for you if needed.  To manually build it, first do the [system setup](/docs/setup.md), then run:
```bash
./build.sh cudf
```
The dependencies from above will be built into the container, and it'll be tested during.  See [`./build.sh --help`](/jetson_containers/build.py) for build options.
</details>
