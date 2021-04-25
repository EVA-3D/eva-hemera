---
title: Hemera
uid: EVA / Hemera
type: drive
badges:
    - Official
contributors: 
    - pkucmus
repo_url: https://github.com/EVA-3D/eva-hemera
cad_url: https://cad.onshape.com/documents/371450c83b99fdd5844f4b0c/w/6283a21a1cfe91323a72f862/e/1fc412a1de950c20053d2aaa
satisfies:
    - drive
    - hotend
---
# Hemera

![preview](assets/Hemera.__ALL__.png)

E3D Hemera is another example of the front heavy EVAs. The motor is huge and the whole extruder takes a lot of space so make sure to understand that the full print volume may not be accessible when using this EVA variant.

??? question "Why not bellow the rail?"

    I tried that on Aero - more informatino there.

Hemera's motor needs to be put on quite early in the assembly process, remember to grab the right belt before putting it on.

### Bill of materials

=== "MGN12"

    <add-bom-button name="{{ meta.uid }} (MGN12)">
        {{ bom_to_json("Hemera.MGN12.csv") }}
    </add-bom-button>
    
    {{ bom_to_md_table("Hemera.MGN12.csv", 4) }}


=== "MGN15"

    <add-bom-button name="{{ meta.uid }} (MGN15)">
        {{ bom_to_json("Hemera.MGN15.csv") }}
    </add-bom-button>
    
    {{ bom_to_md_table("Hemera.MGN15.csv", 4) }}

### Links

{{ eva_download_button() }}
