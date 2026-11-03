# 全自动商用咖啡机 / Automated Commercial Coffee

本仓库是全自动商用咖啡机项目的**起始骨架**，用来承接硬件、固件和软件的设计与实现。

This repository is the **starting skeleton** for designing and building a fully automated commercial coffee machine: hardware, firmware, and software.

## 项目目的 / Purpose

设计并研制一台面向商用场景的全自动咖啡机。工作范围包括机械与电气硬件、嵌入式固件，以及配套的控制与业务软件。

Design and build a fully automated coffee machine for commercial service. The scope covers mechanical and electrical hardware, embedded firmware, and the control and business software that runs with the machine.

## 仓库结构 / Layout

| 目录 Path | 用途 Use |
| --- | --- |
| `docs/` | 放进 Git 的短文档、图示和决策记录。较长的文档放在下方 Google Drive。 Short docs, diagrams, and decision records kept in Git. Longer documents live in Google Drive below. |
| `firmware/` | 嵌入式固件：控制器、传感器与执行器。 Embedded firmware for the controller, sensors, and actuators. |
| `hardware/` | 机械结构、原理图、PCB 与 BOM。 Mechanical design, schematics, PCB, and BOM. |
| `software/` | 上位机、接口，以及运营与配置软件。 Host tools, interfaces, and operations or configuration software. |
| `research/` | 调研笔记、参考资料索引和实验记录。 Research notes, reference indexes, and experiment logs. |

## 建议的下一步 / Suggested next steps

1. 在 Google Drive 建立文档目录，并把下面的占位链接换成真实地址。 Create the Google Drive folders and replace the placeholder links below.
2. 写一页产品范围：出杯流程、机型边界，以及必须的传感器与执行器。 Write a one-page product scope: brew flow, machine boundaries, and the required sensors and actuators.
3. 选定主控与电气架构后，再在 `firmware/` 放入真实工程。 Choose the controller and electrical architecture, then add a real project under `firmware/`.
4. 在 `hardware/` 开始第一版机械与电气草图。 Start the first mechanical and electrical sketches in `hardware/`.
5. 约定分支、评审和硬件版本的命名方式，再展开功能开发。 Agree on branching, review, and hardware revision names, then start feature work.

## 文档 / Documents

以下链接是占位。Google Drive 目录建好后，替换成实际链接。

These links are placeholders. Replace them with the real Google Drive URLs once those folders exist.

| 文档 Document | 链接 Link |
| --- | --- |
| 产品需求与规格 Product requirements | https://drive.google.com/drive/folders/REPLACE_WITH_REQUIREMENTS |
| 机械与电气设计 Mechanical and electrical design | https://drive.google.com/drive/folders/REPLACE_WITH_HARDWARE_DOCS |
| 固件与软件架构 Firmware and software architecture | https://drive.google.com/drive/folders/REPLACE_WITH_SOFTWARE_DOCS |
| 调研与实验 Research and experiments | https://drive.google.com/drive/folders/REPLACE_WITH_RESEARCH |
| 会议与决策记录 Meetings and decisions | https://drive.google.com/drive/folders/REPLACE_WITH_MEETINGS |

## 状态 / Status

起始骨架。目录已经就位，后续设计与实现放进上表中的对应目录。

Starting skeleton. The layout is in place; later design and implementation go in the folders above.
