# idTech4CaS

This is a Contrast Adaptive Sharpening implementation for Prey and Quake 4. The shader used here is a direct copy of https://pastebin.com/iUmDXTVP, which is a copy of AMD's implementation here: https://gpuopen.com/gaming-product/fidelityfx/

This will only work in 1024x768 or 1280x1024 (r_mode 5 or r_mode 7) this is because I can't figure out how to pass the screen resolution down to the ARB shaders, since the engine for Prey and Quake 4 isn't released, and I don't think enough is exposed to do that. Let me know if I'm wrong.

g_casUpscale is 1 by default(which means its on), 0 means off.

DLL compiled against Prey 1.3 and Quake 4 l.4.3

