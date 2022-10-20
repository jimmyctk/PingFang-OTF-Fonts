# PingFang-OTF-Fonts
PingFang extracted in OTF using [Adobe Font Development Kit for OpenType AFDKO](https://github.com/adobe-type-tools/afdko)

---
## Installing
1. Create a virtual environment:
```
python3 -m venv afdko_env
```

2. Activate the virtual environment:

macOS & Linux
```
source afdko_env/bin/activate 
```

Windows
```
afdko_env\Scripts\activate.bat
```

3. Install afdko:
```
pip3 install afdko
```

---

## Pre-requistince
- Use the font inside this repo or 
- Extract from a Mac "/System/Library/Fonts/" or
- Find any ttc
---
## Usage
```otc2otf PingFang.ttc```

```sh PingFang.sh```
