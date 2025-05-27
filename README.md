# 🎮 Sonorització d’un videojoc utilitzant Wwise

Integració completa i funcional d’àudio per a un videojoc mitjançant el middleware **Wwise 2023.1.4.8496**. Aquesta pràctica forma part de l’assignatura *Àudio Digital* (Curs 2024/25) i aplica conceptes clau de disseny de so interactiu i flux de treball entre Wwise i motors com Unity o Unreal.

## 👤 Autors

**Pau Mena Torres**
**Edgar Mesa Domínguez**

## ✅ Objectius de la pràctica

- Integrar sons d’accions bàsiques (inventari, destrucció, etc.).
- Configurar àudio ambient diürn i nocturn amb paràmetre **RTPC Time_of_Day**.
- Aplicar sons 3D amb atenuació per distància.
- Sons de petjades adaptats a superfície (**Surface_Type**) i opcionalment a velocitat (**Player_MovementSpeed**).
- Sons d’impacte d’armes segons el tipus d’arma (**Player_Weapon**) i superfície.
- Control del volum mitjançant sliders del menú (**MenuSlider_Master_Volume** i **MenuSlider_Music_Volume**).
- Aplicació de **reverberació** segons l'espai (coves i masmorres).
- Integració de **loop musical** a la zona **Music_Region**.
- Generació de **SoundBanks** per fer funcionar tots els sons al joc.

## 🔧 Tasques implementades

- [x] Events: Inventory, Quest Roll, Destruction
- [x] Ambient amb RTPC (Time_of_Day)
- [x] 3D Emitters amb atenuació
- [x] Petjades adaptades a superfície (Surface_Type)
- [x] Impactes d’armes segons superfície i tipus d’arma
- [x] Sliders de volum en menú
- [x] Reverberació en:
  - Cave
  - Dungeon_Forge
  - Dungeon_Library_Statue
- [x] Loop musical en Music_Region
- [x] SoundBanks generats correctament

## ℹ Requisits

- **Wwise 2023.1.4.8496** (obligatori)
- Unity o Unreal per a proves d’integració
- Paquets de so:
  - `Sounds - WAG Originals_1.zip`
  - `Sounds - WAG Originals_2.zip`
