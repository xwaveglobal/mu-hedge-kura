# assets/minis — PLACEHOLDER ART

The original 12 UI images (loading_bg, icon_192/512, btn_home/revisit/share, paw_thumb,
pop_home_art, pop_home_steps, pop_revisit_profile, pop_revisit_coins, pop_share_art) were never
pushed to this repo, so `src/build_native.py` failed. These files are generated placeholders with
the same names and aspect ratios so the TikTok native build runs.

Replace each file with the real HedgeKura v2 art (same file name; keep the aspect ratio:
pop_home_art 640x217, pop_revisit_profile 640x362, pop_revisit_coins 762x283, pop_share_art 640x451),
then rebuild with `python3 src/build_native.py`.
