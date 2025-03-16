# Setup Instructions

## 🔧 Setup
1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Install Solc:
```bash
brew install solc-select
```

## ✅ Ready to Use

Once the setup is complete, you can compile smart contracts into bytecode:
```
python3.11 compile.py [-h] [--solidifi] [--smartbugs] [--slise] [--longest-bytecode]
```

---

## Dataset used
1. https://github.com/DependableSystemsLab/SolidiFI-benchmark
2. https://github.com/DependableSystemsLab/SolidiFI
3. https://github.com/smartbugs/smartbugs-curated