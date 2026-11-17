# Hookshot OOT Recomp (v2.3.2)

**Hookshot OOT Recomp** statically recompiles the Switch 2 Ocarina of Time remake (`0400486024DEC000`, `v131072`) into a native Vulkan binary without an emulator (`git.notrexed.dev/Hookshot/Hookshot`).

<img width="320" height="277" alt="images1" src="https://github.com/user-attachments/assets/3804fb64-b317-407c-87c7-0871e8fa4102" />
<img width="1600" height="985" alt="images2" src="https://github.com/user-attachments/assets/24643430-a73a-423f-8ebf-95567b60b23c" />

## Native Highlights in v2.3.2
* **Save Backups & `--user` Mode**: Keeps the newest 20 save backups outside the game folder and isolates settings across updates.
* **Intel XeSS, DLSS & CRT Filters**: Adds XeSS + Native AA, CRT TV/monitor filters in the Insert menu, and auto VRAM budgets.
* **Vulkan-Only Builds & GPU Fixes**: Shorter Windows builds, Arc B580 parallel shader compile, and NVIDIA water device-lost fixes.

<img width="500" height="280" alt="images3" src="https://github.com/user-attachments/assets/a77ee096-db1e-4c9f-9b9c-8e845804311a" />
<img width="576" height="324" alt="images4" src="https://github.com/user-attachments/assets/a4e98c19-8019-4ef6-bcdd-9544a1af924a" />

### Recompile From Your Own `.nup` Copy
```text
HookshotBuilder.exe  -> select your own .nup or romfs+exefs -> native vulkan executable
```

<img width="576" height="324" alt="images5" src="https://github.com/user-attachments/assets/625b6035-d1d5-4571-a37b-21df329f21b9" />
<img width="640" height="480" alt="images6" src="https://github.com/user-attachments/assets/1db5aaf7-be46-42cd-9df6-b9cdc03c6c2e" />
