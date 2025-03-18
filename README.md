# go2_mujoco_playground

Unitree Go2 integration in Mujoco playground framework.

## Installation Instructions

Follow these steps to integrate the Go2 module into the Mujoco Playground framework.

### 1. Clone the original Mujoco Playground repository

First, clone the official Mujoco Playground repository and navigate into it:

```bash
git clone git@github.com:google-deepmind/mujoco_playground.git && cd mujoco_playground
```

### 2. Navigate to the locomotion directory
Move into the locomotion directory where you will clone the Go2 module:

```bash
cd mujoco_playground/_src/locomotion
```

### 3. Clone the Go2 Mujoco Playground repository

Now, clone the Go2 Mujoco Playground repository into the locomotion directory:

```bash
git clone https://github.com/DimitrisGkoutzounis/go2_mujoco_playground.git
```
**Note:** Move the executables in the experimenta/sim2/sim directory and keep the go2 folder, under the locomotion folder.

### 4. Install the Go2 module

To integrate the new module with Mujoco Playground, run the following command:

```bash
pip install -e .
``` 
