<p align="center">
  <img src="Docs/Banner/AToR_Banner.png" alt="AToR Banner"/>
</p>

# AToR : All Types of Resistance (BG3 mod)

This is a mod for the game Baldur's Gate 3.

The purpose of this mod is to display **All Types of Resistance** including ones without any immunity, resistance or weakness.

Also improve Character and Party panel for Spell Book UI in general (Class info / Spell list / Reactions)

## 🔖 Version
- 📦 **AToR** mod : `1.2.0`
- 🎮 **BG3** compatible : `4.1.1`

## ✨ Features

- Display **all** types of resistance including ones without any immunity, resistance or weakness.
- Resistances are divided into **3 rows** and **rearranged**.
- **Reverse order** between Resistances and Conditions.
- Some icons are reworked for a **better visual**.
- **Tooltip added** for damage type without any immunity, resistance or weakness.

### 🎁 Bonus :

**BIG** rework of the whole **Spell Book UI** ( Class info / Spells / Reactions ) in Character and Party Panels, it's actually much more than just *All Types of Resistance* now ! 😅
- The user interface is now *responsive* to be compatible with all variations of **BCPP** mods.
- Extend the **size** of useful content in Party Panel.
- **Align** everything in its right place.
- Replace some backgrounds and sprites to **fix artifacts** in vanilla images ( Party Panel Bg, Tabs, ... ).

## 🔀 Compatibility

### 📄 Files :

This mod changes the following files of the game :

- Public\Game\GUI\Library\
  - **CharacterSheetTemplates_k.xaml**
  - **Tooltips.xaml**
  - **Images_k.xaml**
  
### 👽 Other mods :

#### 🟢 **Compatible** with the following mods :
- **Better Character and Party Panels** ( *BCPP* ) *All variants* : Tested with BCPP v1.5.9

#### 🟡 Compatible with **minor bugs** :
- **Better Tooltips** ( *BT* ) : Tested with BT v1.0.8

  - **Minor Bug** : Tooltips for no resistance/immunity/vulnerable are displayed as *vulnerable* 
  ( **Believe in the icon** and not the tooltip )
  
  - **Install** : You **have to** rename `BetterTooltips.pak` file from *BT* mod into `50_BetterTooltips.pak`
because *BT* needs to overwrite my mod's files and it doesn't work conventionally (Like with BG3MM).

#### 🔴 **Not compatible** with the following mods :
- **Better Target Info**

*NB : I am currently working on it to make this possible. Stay tuned ❗*

## 💾 Install

### Download the mod : 
- [GitHub](https://github.com/Coyote-31/bg3-all-types-of-resistance/releases)
- [NexusMods](https://www.nexusmods.com/baldursgate3/mods/6458)

### Manual :
Drop the `.pak` file from the `.zip` archive inside the folder :

    %LocalAppData%\Larian Studios\Baldur's Gate 3\Mods

### Manager :
- With `BG3 Mod Manager` : The mod should be in **Overrides**.
- With `Vortex` : Mark the mod as **replacer**.

## ❌ Uninstall

### Manual :
Remove the mod's `.pak` file from :

    %LocalAppData%\Larian Studios\Baldur's Gate 3\Mods

### Manager :

- With `BG3 Mod Manager`.
- With `Vortex`.

## 🔍 Screenshots

### All resistance icons grouped & ordered :

<p align="center">
  <img src="Docs/Screenshots/Inspect_creature_Mizora.png" alt="Inspect creature Mizora"/>
</p>


### Tooltips :

<p align="center">
  <img src="Docs/Screenshots/Tooltips.png" alt="Tooltips"/>
</p>

### Character panel :

<p align="center">
  <img src="Docs/Screenshots/CharPanel_Karlach.png" alt="Character panel"/>
</p>

### Resistances none :

<p align="center">
  <img src="Docs/Screenshots/Resistances_none.png" alt="Resistances none"/>
</p>


### Inspect items :

<p align="center">
  <img src="Docs/Screenshots/Inspect_item_books.png" alt="Inspect item books"/>
</p>

### Party tab :

<p align="center">
  <img src="Docs/Screenshots/Party_tab_vanilla.png" alt="Party tab vanilla"/>
</p>

<p align="center">
  <img src="Docs/Screenshots/Party_tab_modded.png" alt="Party tab modded"/>
</p>
