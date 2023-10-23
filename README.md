# AMS_temp_slave_project

## Overview
- AMSの温度監視プログラム
- スレーブ側
- 2023年度10月時点でテスト中

## Requirement
### Development
- VScode + PlatformIO
### Boards
- [AMS_Temp_Iso_ver2](https://github.com/TUT-ProjectEV/AMS_Temp_Iso_ver2)
### Libraries
- MsTimer2 \@ ^1.1

## Usage
- ライブラリにしてまとめる予定

## Features
- 1Byteごとのメッセージに10bitのADCの値をいれて送信するため少しわかりづらい
- マスター側のライブラリで処理は実装済みのため、読み出しは楽にしてある

## Reference

## Author
- Takamura
    - [GitHub](https://github.com/ST04-tkmr)

## License
- Copyright (c) 2023 東京工科大学 ProjectEV [Released under the MIT license](https://github.com/TUT-ProjectEV/AMS-temp-slave-project-2023/blob/main/LICENSE)
