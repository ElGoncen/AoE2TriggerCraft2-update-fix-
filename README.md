# Trigger Craft II
MegaDusknoir's original project
https://github.com/MegaDusknoir/AoE2TriggerCraft2


A Scenario GUI Editor in Python, for **Age of Empires 2 Definitive Edition**.

[AoE2TriggerCraft](https://github.com/MegaDusknoir/AoE2TriggerCraft) is the predecessor of this project.

一种基于 Python 的 帝国时代2决定版 场景编辑器。

[AoE2TriggerCraft](https://github.com/MegaDusknoir/AoE2TriggerCraft) 是该项目的前身。

actualización del código Python con ayuda de AI
Updating Python code with the help of AI

## Usage

For general users, extract zip file and run

[Download](https://github.com/ElGoncen/AoE2TriggerCraft2-update-fix/releases/latest) 

Manual (Not yet created)

普通玩家可直接解压并运行

[下载](https://github.com/MegaDusknoir/AoE2TriggerCraft2/releases/latest)

[使用手册](https://github.com/MegaDusknoir/AoE2TriggerCraft2/wiki/Manual-(%E4%B8%AD%E6%96%87))

## Getting Started

### Prerequisites
Install AoE2ScenarioParser
```
pip install AoE2ScenarioParser Pillow ttkbootstrap parse genieutils-py jsonschema
```

### Preprocessing
Run
```
python prebuild.py
```

Run or Click to Run, follow the GUI to generate the dataset jsons:
```
python tools\datasetGeneratorGUI.pyw
```
### Start
Run
```
python main.py
```

### Pack
Install pyinstaller
```
pip install pyinstaller
```

Run
```
pyinstaller --noconfirm --onefile --windowed --name "AoE2TriggerCraft2" --collect-all ttkbootstrap --collect-all AoE2ScenarioParser --copy-metadata AoE2ScenarioParser main.py
```

## License

[GNU General Public License v3.0](LICENSE)

## Acknowledgments

Powered by [AoE2ScenarioParser](https://github.com/KSneijders/AoE2ScenarioParser)

Dataset generation uses [genieutils-py](https://github.com/SiegeEngineers/genieutils-py)
