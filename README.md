# MPC Protocol Reference Implementation

The primacy goal of this repo is to provide a _reference implementation_ of popular MPC protocols in SageMath. Main focus is on _correctness_ as opposed to performance. However, this repo can also be used for generating test vectors for performance oriented implementations in C/C++, Rust or Swift.

The secondary goal is to "implement the simulator" that simulates the view of the adversary. While simulators are purely thought experiments, MPC literature if often too imprecise about them. By using SageMath as a common language, the goal is to fill in all the details so that one is convinced about the security guarantees.

To use this repo, you need access to latest SageMath. Run the script [setup_python.sh](./setup_python.sh) (after updating the variable `SAGE` in `setup_python.sh` with the actual path to SageMath executable) to create a SageMath Virtual Environment.

## Sage Resources
* [installation guide](https://doc.sagemath.org/html/en/installation/index.html).
* Running Sage as [Jupyter Notebook](https://doc.sagemath.org/html/en/installation/launching.html)
* VSCode [Jupter Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). (Supports inline python debugging!!!)