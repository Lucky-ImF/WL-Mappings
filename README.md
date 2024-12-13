# WL mappings archive

A collection of mapping (usmap) files for various Wild Life builds.

The latest mapping file was created using [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS).¹

| Build      | UE version | Mapping file              |
| ---------- | ---------- | ------------------------- |
| 2024.12.13 | UE 5.4     | `Mappings_20241213.usmap` |
| 2024.10.17 | UE 5.4     | `Mappings_20241017.usmap` |
| 2024.08.22 | UE 5.4     | `Mappings_20240822.usmap` |
| 2024.06.14 | UE 5.3     | `Mappings_20240614.usmap` |
| 2024.04.19 | UE 5.3     | `Mappings_20240419.usmap` |
| 2024.02.23 | UE 5.3     | `Mappings_20240223.usmap` |
| 2023.12.14 | UE 5.3     | `Mappings_20231214.usmap` |
| 2023.10.20 | UE 5.2     | `Mappings_20231020.usmap` |

[1] To be precise, the mapping was created using `UE4SS_v3.0.1-215-g0b367ff` along with the following AOB:

```lua
-- ue4ss/UE4SS_Signatures/FText_Constructor.lua
function Register()
    return "40 53 57 48 83 EC 48 48 89 6C 24 68 48 8B FA 48 89 74 24 70 48 8B D9 33 F6 4C 89 74 24 40 83 7A 08 01 89 74 24 60 ?? ?? ?? ?? ?? ?? ?? 48 8B F0 48 8B 38 48 85 FF ?? ?? 48 8B 17 48 8B CF"
end

function OnMatchFound(MatchAddress)
    return MatchAddress
end
```
