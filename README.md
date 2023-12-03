# Out-of-Core Graph Neural Network

## TODO List

- [ ] Implement data types for the project.
- [ ] Ensure proper export of the project root directory to the environment variable `OOC_GNN_ROOT`.
- [ ] Download and extract the Cora dataset under the `data` directory.
- [ ] Define and implement necessary functions for the project.
- [ ] Implement resource management strategies.
- [ ] Verify proper configuration of the environment variable in the IDE.
- [ ] Set up the build process according to the provided instructions.
- [ ] Introduce Object-Oriented Programming concepts to the project.
- [ ] Continue implementing Object-Oriented Programming concepts.
- [ ] Explore and implement template functionalities.
- [ ] Incorporate Standard Template Library (STL) components into the project.
- [ ] Implement performance modeling for the project.
- [ ] Optimize the code based on performance analysis.
- [ ] Address any legacy code or plan for future improvements.
- [ ] Ensure the completion of the project and necessary closing tasks.

## Build instructions

1. Export the project root directory to the environment variable `OOC_GNN_ROOT`.
   ```shell
   export OOC_GNN_ROOT="$PWD"


If you are using an IDE, configure the environment variable accordingly.
Download the Cora dataset and extract under the data directory.
The structure of the data directory should be:

ooc-gnn
 |-- data
 |   |-- cora/
 |   |   |-- cora.cites
 |   |   |-- cora.content

    Clone Google Test

    shell

mkdir Google_tests
cd Google_tests
git clone https://github.com/google/googletest.git

Build

shell

mkdir cmake-build-debug
cd cmake-build-debug
cmake ..
ninja

Test

shell

./cmake-build-debug/Google_tests/Google_Tests_run

Run test loop

shell

./cmake-build-debug/OOC_GNN_run
