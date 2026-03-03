## Installation

1. **Install Lean 4**

   Follow the instructions on the [Lean 4 installation page](https://leanprover.github.io/lean4/doc/quickstart.html) to set up Lean 4. Lean version: 4.29.0-rc1

2. **Clone the repository**

```sh
git clone --recurse-submodules git@github.com:nguyenduchuyiu/ai4math.git
cd APOLLO
```

3. **Install dependencies**

```sh
pip install -r requirements.txt
```

4. **Build Mathlib4**

```sh
cd repl
lake update
lake build
```










