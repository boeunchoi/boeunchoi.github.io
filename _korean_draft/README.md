# Korean version (EN <-> 한 slider), set aside Nov 2026

- korean-switch.patch: changes to existing files (slider in header.liquid, slider CSS in custom.css,
  Noto Sans KR in head.liquid, page language in default.liquid, Korean name in home.liquid,
  shared gallery layout in gallery.md / gallery.yml).
  To bring back: git apply \_korean_draft/korean-switch.patch
- gallery.liquid: goes back to \_layouts/
- pages_ko/: goes back to \_pages/ko/ (Korean home, about, research, gallery)

Jekyll ignores this folder because its name starts with "\_".
