# SeedsPlease-patch-for-Vanilla-Factions-Expanded---Medieval

_Only files necessary for patch were included._
######
* VFE-M = Vanilla Factions Expanded - Medieval
* VGP-VG = VGP Vegetable Garden
######
###### Primarily patches grapes from VFE-M for compatibility with SeedsPlease. 
###### It also checks whether VGP-VG is loaded with VVFE-M, and if so removes the grapes from VGP-VG. 
###### This can easily be scaled to include additional cross checking for other mods that add grapes.
######
**Patches**
1. Modified **0_LoadOnDemand_Addons.XML** to add **PatchOperationLoadOnDemand** for VFE-M
2. Modified **1_Compatibility_Patches.XML** to add two nested **PatchOperationFindMod** in case both VFE-M and VGP-VG are loaded to avoid duplication of VGP-VG grapes.

**Defs_OnDemand**
1. added directory of **VanillaFactionsExpanded_Medieval**
2. added **Items_Seeds_VFEM.XML** for VFE-M grapes seed def
3. added **Recipes_Plants_VFEM.XML** for VFE-M grapes recipe def
