# LegacyV3

message(" - - - Blackfathom Deeps")
file(GLOB_RECURSE sources_BlackfathomDeeps Dungeon/Kalimdor/BlackfathomDeeps/*.cpp Dungeon/Kalimdor/BlackfathomDeeps/*.h)
source_group("Dungeon\\BlackfathomDeeps" FILES ${sources_BlackfathomDeeps})

message(" - - - Culling Of Stratholme")
file(GLOB_RECURSE sources_CullingOfStratholme Dungeon/Kalimdor/CullingOfStratholme/*.cpp Dungeon/Kalimdor/CullingOfStratholme/*.h)
source_group("Dungeon\\CullingOfStratholme" FILES ${sources_CullingOfStratholme})

message(" - - - Dire Maul")
file(GLOB_RECURSE sources_DireMaul Dungeon/Kalimdor/DireMaul/*.cpp Dungeon/Kalimdor/DireMaul/*.h)
source_group("Dungeon\\DireMaul" FILES ${sources_DireMaul})

message(" - - - Escape From Durnholde Keep")
file(GLOB_RECURSE sources_EscapeFromDurnholdeKeep Dungeon/Kalimdor/EscapeFromDurnholdeKeep/*.cpp Dungeon/Kalimdor/EscapeFromDurnholdeKeep/*.h)
source_group("Dungeon\\EscapeFromDurnholdeKeep" FILES ${sources_EscapeFromDurnholdeKeep})

message(" - - - Maraudon")
file(GLOB_RECURSE sources_Maraudon Dungeon/Kalimdor/Maraudon/*.cpp Dungeon/Kalimdor/Maraudon/*.h)
source_group("Dungeon\\Maraudon" FILES ${sources_Maraudon})

message(" - - - Ragefire Chasm")
file(GLOB_RECURSE sources_RagefireChasm Dungeon/Kalimdor/RagefireChasm/*.cpp Dungeon/Kalimdor/RagefireChasm/*.h)
source_group("Dungeon\\RagefireChasm" FILES ${sources_RagefireChasm})

message(" - - - Razorfen Downs")
file(GLOB_RECURSE sources_RazorfenDowns Dungeon/Kalimdor/RazorfenDowns/*.cpp Dungeon/Kalimdor/RazorfenDowns/*.h)
source_group("Dungeon\\RazorfenDowns" FILES ${sources_RazorfenDowns})

message(" - - - Razorfen Kraul")
file(GLOB_RECURSE sources_RazorfenKraul Dungeon/Kalimdor/RazorfenKraul/*.cpp Dungeon/Kalimdor/RazorfenKraul/*.h)
source_group("Dungeon\\RazorfenKraul" FILES ${sources_RazorfenKraul})

message(" - - - The Black Morass")
file(GLOB_RECURSE sources_TheBlackMorass Dungeon/Kalimdor/TheBlackMorass/*.cpp Dungeon/Kalimdor/TheBlackMorass/*.h)
source_group("Dungeon\\TheBlackMorass" FILES ${sources_TheBlackMorass})

message(" - - - Wailing Caverns")
file(GLOB_RECURSE sources_WailingCaverns Dungeon/Kalimdor/WailingCaverns/*.cpp Dungeon/Kalimdor/WailingCaverns/*.h)
source_group("Dungeon\\WailingCaverns" FILES ${sources_WailingCaverns})

message(" - - - Zul'Farrak")
file(GLOB_RECURSE sources_ZulFarrak Dungeon/Kalimdor/ZulFarrak/*.cpp Dungeon/Kalimdor/ZulFarrak/*.h)
source_group("Dungeon\\ZulFarrak" FILES ${sources_ZulFarrak})

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  ${sources_BlackfathomDeeps}
  ${sources_CullingOfStratholme}
  ${sources_DireMaul}
  ${sources_EscapeFromDurnholdeKeep}
  ${sources_Maraudon}
  ${sources_RagefireChasm}
  ${sources_RazorfenDowns}
  ${sources_RazorfenKraul}
  ${sources_TheBlackMorass}
  ${sources_WailingCaverns}
  ${sources_ZulFarrak}
)
