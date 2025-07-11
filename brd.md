# �������� � ������-������������ (BRD) ��� ����������� ��������� LTX �������� S.T.A.L.K.E.R.: ��� �������

## 1. ���� � ������ �������

**����:** ������� ���������� �������� �������� ��� ���� S.T.A.L.K.E.R.: ��� �������.

**������� ������:** ���������������, ��� ����� ��������, � ������� ��������������, � ����� ����-����������� �������
�������� � �������������� ������� �������� � ������������ ������� ������ �����������

�� ��������:

1) ����� �� � DLTX �������� ������� ����� ����� � ����� ����� root file ������� ����� ������������ ��� ��������� 
��������� ������?
2) �� ������ ��� ��, ��� ���������� ��� ����� � xml ��������. ��� ������� ���������� ���� �� ������� ����� �������
   ������
3) ����� �� ��������� � �����-������ ���������� ���� Idea/VSCode ����� ����� ���� ���� ��������� �� ��������� ��������
4) � ������ ����� ������������ ������ ����-��������� ��� ��������� ����� ������������� � ����� ����������, ��������, ����������
   ����� � ���������:

```
inv_grid_width		= 2
inv_grid_height 	= 2
inv_grid_x		= 0
inv_grid_y		= 18
```

### ���������� ������ ��� ���������� ����:

1. ������� ������ ������� ��� ���������� ������ ������ � ����� ����� � ���. �� ������� ����� ����� ����������� ������ �
   ������� �� ����� � ����� ���� �����. � ������ ������ ��������� ����� ����� ��������� ���������� ��� ����� �����
   �����.
2. ������� ��� ��������.
3. �������������� �������� �� �� � ��� ������� �����.
4. �������������� �������� �� ������� ���� �����

## 2. �������� ��������

* ������ �� ���������� �������� ����������� ��� �������������� �������� ����� ����
* ������ �� ���������� �������� ����������� ��� �������������� �������� ���� ������ �����
* �� ����� ������ ������� ���������� ����� ���� �� ��� �������� � ������������ ��������� �� ������ ����� ���������
* �� ��� ��� ��������� �������� ����� Idea �� ���������, � � ��� ������ ����������� ������� ����� ����� ���
  �������� ������ ����������� ���������
* �� � ������ ���������� ������� ������� �� �������� ����� �����, � �� ����� ������+���.

## 3. ��� ������ � ������

1. ��� �������� ��������
2. �������� ����� ����� ������ � �����
3. ���������� ��� ���������� ����� ����� ����� � ������

## 4. ��� �� ������ � ������

(������ ������ ������������ ��� ����������� ������ ������� � ��������� �� ����������. � ��������������� ����������
���������� ������ ��� ����� ������� �����������.)

## 5. ������-����������

���� ������ ���������, ��� ������� ������ ��������� ������ ������� ��� ������������ ��� ���������� �����.

### 5.0. ������� ������ ���������

1) �������� ����� ������ �������� � ����/����/������
2) �������� ����� ���� ����� ���� � ������
3) �������� ����� �������� ��������� ���� ������
4) ��������� �������� DLTX

### 5.1. ������ � �������

#### 5.1.1 ������������� �������� �������

��� ��������� ����� � ������ ����� ����������� ���������� ����� ��������� gamedata � ������������ ���������, ��������� �
������� � ��� �����

#### 5.1.2 ����������� ������ � �������

* ����������� ���������� ��������� ����� gamedata
* ����������� ���������������� �� ����� gamedata ��� ������ ����
* ����������� ���������, ���������, ��������� � ������� �������
* ����������� ��������� ��������� ��� ��������� ��� � �������������� DLTX
* ����������� ���������� ���� ��� "������". ��� ����� �������� ����� ��������������
  ����������� [���������](#541-������������-�-��������������-logic-��������)

### 5.2. ������ � ������ ������

* ������ ���� ����������� ��������� ����� ���� ������, �.�. ���������� ����� ���������, �� �� ����������� ����, ����� �
  ���� ������
* ������ ���� ����������� ��������� ��� ������ "������������", ��� �������������� ������ ��� ������������ �����, ���
  ������ ���� ����� ������������ ����� ��������� ������� ����� ������������ � ������, ������� ����� ����
  �) ������� ��� �) ������ ������� � ����� (� ����� � ���� ������) ����� ��������
  ���� [������ ����� ������� ����](#list_dif_fields)

```
; amount, chance
[trade_generic_buy]
;���������
af_cristall				= 1, 0.6
af_fireball				= 1, 0.6
af_dummy_glassbeads		        = 1, 0.6
drug_booster		                ;NO TRADE
```

* ������ ���� ����������� ��������� ��� ������ 1) ����� ������ 2) ���������� ������� ����� 3) ����� ����� 4) ���� �����
* ������ ���� ����������� � ����� ��������� ������ ���� ����� � ����� � �������, ����� ����� ���� ������ ���� ����� �
  ��� ������������ �������
* ������ ���� ����������� ������� �������� ������ � ���� �� �����
* ������ ���� ����������� "�����������" ������ � ������ ����, ����� ����� ���� ���������� ������ ����� �������
* ������ ���� ����������� �������� ����������� � ���� ��� ����� ��������� ��� `a = 1;�����������`
* ������ ���� ����������� ��������� ���� ���� �����������, ������� ����� ��������� ��� `;�����������`, ���� �� ����� ���
  �������� � ������������, �.�. ����� �������� ��������� � ��� ����� ��� ����
* ������ ���� ����������� �������� ����������� � c����� ��� ����� ��������� ���

```
;�����������
[������]
```

* ������ ���� ����������� ���������/������� ������������ ������
* ������ ���� ����������� ������������� � ������������ ������
* <��������� DLTX>

### 5.3. ������ � ������

* ������ ���� ����������� ��������� ����� ���� �����, ������� ����� ����� ������������ ��������� � ���������
* ������ ���� ����������� �������� ���������� � ����, ������� ����� ������������ � ���������
* ������ ���� ��� "����������", ������� ����� �������������� ��� �����, ������� �� �������������� ����������, �� �����
  ���� � ������
* <��������� DLTX>
* ������ ���� ����������� ����������, ����� �� ���� ��� ���� ���� �������, �.�. ����� �� ���� ���������
  ��������� ��������, ����������� �������� ��� ���������� ������������ ������������.
* �� ��������� ������ ���� ��� ���� ����� � ���������� �����������, ��� + �������� ����� �� ���� �������:
    * +**����������**: ��� �������� ���� ����� ��������� ��� ���� ������ - `a = literally anything`
    * +**������**: `af_quest_b14_twisted = true`
    * +**���� �� ����� �� ����� �� gamedata**: ���� ��� ������ �������������� ���� ����� �� ����� �� ����� � gamedata �
      ������ "��� �������". **������**: `blood = wm\wm_blood_1` - ��� `wm\wm_blood_1.thm` - ��� ������������� ���� ��
      �����
      � ����� `textures` � `gamedata`
    * -**����������**: ���������� ���������� - `rating = novice, 300, experienced, 600, veteran, 900, master`
    * -**������������ ������**: ������ �� ��������� ��� ������� ��������� ���������� ����� -
      `communities		= actor, 0, bandit, 1, dolg, 2, ecolog, 3, freedom, 4, killer, 5, army, 6, monolith, 7, monster, 8, stalker, 9, zombied, 10`
    * +**�������� ������**: � ������ `��������`, ��� �������� �������� ������ ������ �� �����/��������������� ������ -
      `character_profile     = sim_default_duty_1`
    * +**�������� �� ������������� ������**: ���� � ������� ���������� �������� �� ������������� ������ -
      `community = dolg`
    * +**����������� ������**: ���� �� �������� ����� ����� ������ � ��������� ���� -
      `name = ui_inv_outfit_chemical_burn_protection`
    * +**������**: �������� ������? - `icon     = ui_am_prop_chem`
    * +**�������**: �������� ����� � ������� �� ���� - `functor  = inventory_upgrades.property_functor_a`
    * -**�������**: ����� �������� �� ������-�� �� ������-�� - `antirad					= 0.08`
    * -**��������**: �� ��� ������, ��� ��������� [������](#54-������������-�-��������������-condlists)
        * ������ ���� ����������� ������� ������������ ���: bool, ������ ��� ������ (**!!!** ���� �� ���-�� ���?)
    * <a name="list_dif_fields"></a>-**������ ����� ������� ����**: �������� ��������� ����� ������ �����, �����������
      ��������. ����� ����� � �������
      �������� ���� ��������� � ������ � ���������

```
;----------------------------------------------------------------------------------------------------------------------------------------
;format:       time(sec),	sound_name,	       light_R, G,   B,    light_range, particle_name,			        af_animation_name
;----------------------------------------------------------------------------------------------------------------------------------------
starting =	5.0,		anomaly\gravi_idle00,	0.5,    1.0, 1.5,  5.0,	       "anomaly2\artefact_gravi_blast_start",	"idle"
```

P.S. ��� ��� ���� ����� ������� ����� ������� ���� ���������, �� ����� �� ������. ��������,
`full_scale_icon` � `outfit.ltx`

### 5.4. ������������ � �������������� condlists

**��� ����� Condlist?**
`Condlist` (Condition List) � ��� ������ ��������� ������������ ���������������� ������, ����������� ��������� ���������
�������� ��� ���������� ������ �������� � ����������� �� �������. �� ������� �� ������ ������� � ������������ ��������,
� ����� ����� �������� �������.  `Condlists` ������������ � ������� ������ ��� ����������� ������ �������, ��������� NPC
� ������ ������������ ������.

**������� ������������� � ����:**

* `precondition`: ���������� ������� ��� ������ ������ NPC. ��������, `precondition = {=random_chance(100)} true, false`
  ��� `precondition = {=is_rain} true, false` .
* `on_complete`, `on_init`, `on_fail`, `on_reversed`: ��������� ������� ��� ����� ������� ������ (����������,
  �������������, ������, ������). ������������ �������� `condlist` � ���� ����� ������������. .
* `condlist_N`: ������������ ��� �������� ������� ���������� ������, ������ ���������� "complete", "fail" ��� "
  reversed" .
* `title_functor`, `descr_functor`, `target_functor`: ����� ���� `condlists`, ������������� ��������� �������������� ���
  ������������� ������ ��� ����� .

**���������� � ��������� condlists:**

* ������� ������ ��������������� ������� ������ `condlists` ��� ��������� ��������� � ��������������.
* �������� ������ ������������ �������� � ����������� ������ �������, �������:
    * **�������� ������� (+info), ���������� (-info) ��� ��������� (!info) �������������� ������.**
        * ��������, `+C` �������� `db.actor:has_info("C")`, � `-D` �������� `not db.actor:has_info("D")`.  `!info` (���
          `!B`) �������� `not xr_conditions.B`.
        * ��� �������������� � ���������, �������������� �������������� ������ (��������, ���� ���), ������ �����������
          ����������� ���� � �������: **"��������"** (`+info`), **"����������"** (`-info`), **"������������"** (
          `=info`). (��������, ��� `+pri_a21_task_end` ��� `-simulation_task_52_dead_spawned` ).
    * **����� ���������� � ���������������� ������� ������� (=function_name(arg1:arg2)) �� `xr_conditions.txt`.**
        * �������� ������ ������������� ������� ����� ���� ������� (��������, `actor_has_item`, `is_rain`,
          `squad_exist`, `is_dead` ) � �� ���������� (��������� ���������� `p, p, c`).
    * **�������� ����������� ���������� ������� (~chance).**
        * ��������, `~30` �������� 70% ����, `~80` �������� 20%.
* ������ ���� ��������� ������������� ������ ������� (`{cond1} result1, {cond2} result2, result3`), �����������
  ����������� ������ "if-elseif-else". �������� ������ ��������������� ���������������� �������� ���� ������, ��� ���
  ����������� � ���� ��� �������� `condlist_N`.
* ������� ������ ��������� ��������� � ������������� ������� (`%=effect_name(arg1:arg2)%`) ������ `condlists`.
    * ��������, `%=E(e1)` ��������� `xr_effects.E(game_object_1, game_object_2, {"e1"})`.
    * ������� �������� �� `tm_dynamic.ltx`: `reward_stash(true)`, `inc_goodwill_by_tasker_comm(simulation_task_52:50)`,
      `remove_quest_item(simulation_task_52)` .
    * ������� ����� ���� ���������� ���������, ������������� � `xr_effects`. ��������, `give_tuna_to_actor`.
* **������������ � �������������� ������������� ��������:** ������ ����� ����� `condlist` (�� ��� ����� �������������
  ��������) ����� ���� ��������� �������� (��������, `%=E(e1) +F -G%`), � ����� ��������� �������������� ������ (`+F`,
  `-G`). �������� ������ ��������� ����� ��������� � ��������� ����� ���������/�������/������������� ������ �� ����
  ���������.
* **��������� ������������ ��������:** �������� ������ ������������� ����� �������� �, �� �����������, ��������� ���
  ��������� ������������ �������� `condlists` � ��������� �����.
    * `condlist_N` (������ ���������� ������) ������ ���������� "complete", "fail" ��� "reversed".
    * `precondition` (������� ������ ������) ������ ���������� "true" ��� "false" (��������), ����� �� ��, ����� �� NPC
      ���������� �����.
    * `title_functor`, `descr_functor`, `target_functor` (������������ �����/����) ������ ���������� ���������
      �������������� (��������� ����� ��� ����� ��������) ��� `nil`. ����������� �������� `nil` ��� `target` ��������,
      ��� ����� ���� ����� ���� �������� ������, ���� ������� �� �����������.
    * `on_init`, `on_complete`, `on_reversed`, `on_fail` (������� ��� ����� �������) �� ������ ����� �������������
      ��������, ��� ��� �� ��������� ������������ �������, � ����� ������ �������� �������.
    * `reward_money` � `reward_item` ������ ���������� ����� (��� �����) ��� ������ � ������� ��������� (��� ���������),
      ������� ����� ���� ��������� ���������� (��������, "beer:vodka:vodka2").
* **���������������� ���� ���������� �������:** ��� ������� `xr_conditions` � `xr_effects` (����� ��� `actor_has_item`,
  `is_rain`, `squad_exist`, `is_dead`), �������� ������ ���������� �� ������ ��������� ����, � ����������-���������
  �������� ����������. ��������, ��� �������� ���������� � ���� ����� �����, ��� ������� � ��������, ��� ������ ��
  ������� ��� ������� � ���������� ������ ��� �������� ������, �������� �� ���������� � ��������� ��������� � ��������.
  ��� ����������� �������� ������ � ������ ���������� ������.

### 5.41 ������������ � �������������� logic ��������

* ������������� ���������� ��������� ��������� ����� ������ � �������
* ��������� ��������� ����� ����� ������ �� ������ ����� � ����� **������**
  ![�������� ��������](https://media.discordapp.net/attachments/1381441097615675473/1384462136759029822/434073160-9be6acb7-7dd9-4445-93d9-215a502bdeac.png?ex=68528457&is=685132d7&hm=e7bac63c1b0ec550704f9f9f5d7e35148b3eed3eb93be0ce006f73e78429873c&=&format=webp&quality=lossless)

### 5.5 ��������� �� �����������

��������� �������� ���������� � xml ��������, �� ����� ������� ��������� ������ �����������, �� �������� ����� �����
������������ ������� ����� ����� �������-�������, ��������� ���, ������� � ��� ��������� ����� ���� ����-�������.
�� ������� �� ����������, ������ ����������� ������ ����������� ��� ����� ������� �� ����� ������� ������� ������
�����������, � ����� ����� ������ ������� �� ����. ��� �� ����� ����������� �������/��������� ������ ������ �����������
���� ����.

**!!!** ������, ��� ������ �� ���������, �.�. ����� �������� ��� ��������/����������� ����������. ����
`dialogs_jupiter.actor_relocate_evacuation_info`

### 5.6. ��������� �� �������

�� �������� � VS ����� ������ �� ������ � ����� ��� ������ ������ �� ��� ���������

### 5.7. �������� � ������������

* �������� ������ �������� ��������� ��� �������� ������������ ����������� ������ (��������, �������� ����������
  `condlists` � ������������ ������ �� �������������� ������ ��� ������� Lua).
* �������� ��� ��� ������������ ������ ���-�� �������
* ��� ���� ����� ����� ������ ���� ���������, ������� ��������� ������������ ��������� ������, � ��� ������ �����
  "�������������" ������� �������� � ��������� �� �� ������

### 5.8. ������������������ � �������� �������������

���������� ������������������:
1) ��������� � ���� ��� ������
   1) ������ �� ����� �� �����
   2) ������ �������� ������� ������ �� ��������� ������
   3) ������ �� ��������� ������
2) ��������� �� �������
   1) ��� ��� ������ ������������/����������� � ���� �����
   2) ��� ��� ������ ������������/����������� � ������ ������

### 5.9. �������������� � ������� �����������

* IconEditor
    * �����������\���������� ��� TaskEditor ������, ������� ����� ���� ������������ � ������� �����