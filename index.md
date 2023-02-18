---
layout: default
title: ディレクトリ構造と簡単なマテリアル説明
---

```
.
└── CasualAndCoolJacket/
    ├── CasualAndCoolJacket_X.x/
    │   └── CasualAndCoolJacket_対応アバター名_X.x.unitypackage/
    │       ├── _MA/
    │       │   └── 各アバター用フォルダ/
    │       │       ├── Animations/
    │       │       │   └── ...
    │       │       ├── Contoller/
    │       │       │   └── ...
    │       │       └── ExMenu/
    │       │           └── ...
    │       ├── Animations/
    │       │   └── Outfit Anims Type1
    │       ├── FBX/
    │       │   └── 各アバター用衣装.fbx
    │       ├── Material/
    │       │   ├── lilToon/
    │       │   │   └── ...
    │       │   └── Texture/
    │       │       └── ...
    │       └── Prefab/
    │           └── 各アバター用フォルダ/
    │               ├── 衣装.pre
    │               └── 衣装_MA(ModularAvater用セットアップ済み).pre
    ├── Shader/
    │   ├── ...
    │   └── ...
    └── !ReadMe(Webリンク)
```

- Material/lilToon
  - 1. Jacket <span>- ジャケット用マテリアル</span>
    - 1.1 Fur  <span>- ファー素材</span>
      - 1.1.1 Normal <span>- ラメ無し</span>
      - 1.1.1.1 J_Fur_N_BL(lil)
      - 1.1.1.2 J_Fur_N_BLwith_pocket(lil)
      - 1.1.1.3 J_Fur_N_W(lil)
      - 1.1.2 Glitter <span>- ラメ</span>
      - 1.1.2.1 J_Fur_G_W(lil)
    - 1.2 Knit <span>- ニット素材</span>
      - 1.2.1 Normal <span>- ラメ無し</span>
      - 1.2.1.1 J_Knit_N_BL(lil)
      - 1.2.1.2 J_Knit_N_O(lil) <span>- オレンジアクセントの白</span>
      - 1.2.1.3 J_Knit_N_W(lil)
      - 1.2.1.4 J_Knit_N_Xmas(lil)
      - 1.2.2 Glitter 
      - 1.2.2.1 J_Knit_G_Xmas(lil)
    - 1.3. Normal(opaque) <span>- 不透明</span>
      - 1.3.1 AudioLink <span>- サイバーモチーフ/Audiolink対応</span>
      - 1.3.1.1 J_NO_AudioLink_Cyber_B(lil)
      - 1.3.1.2 J_NO_AudioLink_Cyber_P(lil)
      - 1.3.2 Normal <span>- シンプル/サイバー</span>
      - 1.3.2.1 J_NO_N_BLUE(lil)
      - 1.3.2.2 J_NO_N_Cyber_B(lil)
      - 1.3.2.3 J_NO_N_Cyber_P(lil)
      - 1.3.2.4 J_NO_N_GREEN(lil)
      - 1.3.2.5 J_NO_N_PURPLE(lil)
      - 1.3.4.6 J_NO_N_YELLOW(lil)
    - 1.4 Normal(Trans) <span>- 半透明</span>
      - 1.4.1 ClearTrans <span>- 全体が半透明</span>
      - 1.4.1.1 J_NT_ClearTrans_LV1(lilRefBlur) <span>- 屈折ぼかし</span>
      - 1.4.1.2 J_NT_ClearTrans_LV2(lilRefBlur)  <span>- 屈折ぼかし</span>
      - 1.4.1.3 J_NT_ClearTrans_LV3(lilToon) <span>- 屈折ぼかし無し</span>
      - 1.4.2 Normal <span>- シンプル/一部半透明</span>
      - 1.4.2.1 J_NT_N_GREEN(lil)
      - 1.4.2.2 J_NT_N_PURPLE(lil)
      - 1.4.2.3 J_NT_N_YELLOW(lil)
    - 1.5 Transparent <span>- シンプル/一部半透明</span>
      - 1.5.1 J_T_BLUE(lil)
  - 2. Muffler <span>- マフラー用マテリアル</span>
    - 2.1 Glitter <span>- ラメ</span>
      - 2.1.1 M_G_BLUE(lil)
      - 2.1.2 M_G_BlueGreen(lil)
      - 2.1.3 M_G_GREEN(lil)
      - 2.1.4 M_G_PURPLE(lil)
      - 2.1.5 M_G_RED(lil)
    - 2.2 Normal<span>- シンプル</span>
      - 2.2.1 M_N_BLUE(lil)
      - 2.2.2 M_N_BlueGreen(lil)
      - 2.2.3 M_N_GREEN(lil)
      - 2.2.4 M_N_PURPLE(lil)
      - 2.2.5 M_N_RED(lil)