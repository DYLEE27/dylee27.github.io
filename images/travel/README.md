# travel 사진 폴더

travel 지도의 점을 누르면 뜨는 사진 카드에 들어가는 사진입니다.
**점마다 폴더가 하나씩** 있고, 그 폴더에 `photo.jpg`를 넣으면 자동으로 연결됩니다.

- `sea/` — 파란 점 (바다)
- `nature/` — 초록 점 (자연)

파란 점과 초록 점은 색만 다르고 동작은 같습니다. 언제든 누르면 카드가 뜨고, 사진이 아직 없으면 "사진 준비 중"이 보입니다.

## 사진 넣는 법

1. 해당 폴더에 사진을 넣습니다.
2. 파일 이름을 **`photo.jpg`** 로 바꿉니다. `photo.png`, `photo.jpeg`도 됩니다.
3. 끝. 새로고침하면 보입니다.

## 폴더 목록

| 폴더 | 점 |
|---|---|
| `sea/red-sea/` | 🔵 Red Sea — Hurghada |
| `sea/maldives/` | 🔵 Indian Ocean — Maldives |
| `sea/saipan/` | 🔵 Pacific Ocean — Saipan |
| `sea/cape-town/` | 🔵 Atlantic Ocean — Cape Town |
| `sea/okinawa/` | 🔵 East China Sea — Okinawa |
| `nature/istanbul/` | 🟢 Istanbul |
| `nature/alexandria/` | 🟢 Alexandria |
| `nature/cairo/` | 🟢 Cairo |
| `nature/nairobi/` | 🟢 Nairobi |
| `nature/big-sur/` | 🟢 Big Sur |
| `nature/yosemite/` | 🟢 Yosemite |
| `nature/lake-tahoe/` | 🟢 Lake Tahoe |
| `nature/zion/` | 🟢 Zion |
| `nature/bryce-canyon/` | 🟢 Bryce Canyon |
| `nature/arches/` | 🟢 Arches |
| `nature/monument-valley/` | 🟢 Monument Valley |
| `nature/grand-canyon/` | 🟢 Grand Canyon |
| `nature/sedona/` | 🟢 Sedona |
| `nature/wadi-rum/` | 🟢 Wadi Rum |
| `nature/siwa-oasis/` | 🟢 Siwa Oasis |
| `nature/cape-of-good-hope/` | 🟢 Cape of Good Hope |
| `nature/sossusvlei/` | 🟢 Sossusvlei |
| `nature/etosha/` | 🟢 Etosha |
| `nature/okavango-delta/` | 🟢 Okavango Delta |
| `nature/victoria-falls/` | 🟢 Victoria Falls |
| `nature/erta-ale/` | 🟢 Erta Ale |

새로 초록 점을 만들면(`index.html`의 `DATA.trips`에서 `nature: true`), 폴더 이름은 장소 이름을 소문자로 바꾸고 띄어쓰기를 `-`로 바꾼 것입니다. 예: `Lake Tahoe` → `nature/lake-tahoe/`

## 주의

- 권장 비율은 4:3, 폭 800px 정도입니다. 비율이 달라도 가운데 기준으로 알아서 잘려 보입니다.
- 휴대폰 사진은 용량이 크니 1MB 이하로 줄여서 올리면 빨리 열립니다.
- 각 폴더의 `.gitkeep`은 빈 폴더를 git에 올리기 위한 빈 파일입니다. 지우지 않아도 됩니다.
- 이 폴더 바로 아래에 있는 `sea-*.jpg`, `sea-saipan.png`, `petra.jpg`, `victoria-falls.jpg`, `yosemite.jpg`는 예전 위치의 사본이라 이제 쓰지 않습니다. 지워도 됩니다.

## 지금 들어 있는 데모 사진 (Wikimedia Commons)

내 사진으로 바꾸기 전까지 쓰는 임시 사진입니다. 그대로 공개할 경우 아래 출처·라이선스 표기가 필요합니다.

| 폴더 | 원본 | 작가 | 라이선스 |
|---|---|---|---|
| `sea/red-sea/` | [Coral reefs in Hurghada.JPG](https://commons.wikimedia.org/wiki/File:Coral_reefs_in_Hurghada.JPG) | Aymangabalawy | CC BY-SA 3.0 |
| `sea/maldives/` | [Schnorcheln Mit Schildkröten Malediven](https://commons.wikimedia.org/wiki/File:Schnorcheln_Mit_Schildkr%C3%B6ten_Malediven_(172176477).jpeg) | Dronepicr | CC BY 3.0 |
| `sea/saipan/` | [NOAA diver bigeye scad school Saipan 2022](https://commons.wikimedia.org/wiki/File:NOAA_diver_bigeye_scad_school_Saipan_2022.png) | NOAA Fisheries / Jeff Milisen | Public domain |
| `sea/cape-town/` | [Cape Town (ZA), Sea Point Promenade, Küste](https://commons.wikimedia.org/wiki/File:Cape_Town_(ZA),_Sea_Point_Promenade,_K%C3%BCste_--_2024_--_3632.jpg) | Dietmar Rabich | CC BY-SA 4.0 |
| `nature/yosemite/` | [Tunnel View, Yosemite Valley, Yosemite NP - Diliff](https://commons.wikimedia.org/wiki/File:Tunnel_View,_Yosemite_Valley,_Yosemite_NP_-_Diliff.jpg) | Diliff | CC BY-SA 3.0 |
| `nature/victoria-falls/` | [Cataratas Victoria, Zambia-Zimbabue, 2018-07-27, DD 05](https://commons.wikimedia.org/wiki/File:Cataratas_Victoria,_Zambia-Zimbabue,_2018-07-27,_DD_05.jpg) | Diego Delso | CC BY-SA 4.0 |
