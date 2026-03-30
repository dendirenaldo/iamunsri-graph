# iamunsri-graph

Repositori ini berisi kumpulan diagram untuk dokumentasi sistem IamUNSRI.

## Isi Utama

- **Activity Diagram**: alur proses fitur utama (login/auth, reset password, verifikasi alumni, pendaftaran aktivitas, job application, SSO, voucher redemption).
- **BPMN**: alur bisnis tingkat proses.
- **ERD**: beberapa versi rancangan relasi database (`erd-a` sampai `erd-d`).
- **Use Case Diagram**: skenario aktor utama (user, perusahaan, admin, dan gabungan).
- **System & Dependency Diagram**: arsitektur sistem dan dependensi modul.

## Struktur File

Diagram disimpan dalam beberapa format:

- Sumber diagram: `.d2` dan `.plantuml`
- Hasil render: `.png` dan `.svg`

## Prasyarat (opsional untuk edit/generate ulang)

- [D2](https://d2lang.com/) untuk file `.d2`
- [PlantUML](https://plantuml.com/) untuk file `.plantuml`

## Contoh Generate Ulang Diagram

```bash
# D2 -> PNG
d2 module_dependency_diagram.d2 module_dependency_diagram.d2.png

# D2 -> SVG
d2 module_dependency_diagram.d2 module_dependency_diagram.d2.svg

# PlantUML -> PNG/SVG
plantuml -tpng use_case_diagram-user.plantuml
plantuml -tsvg use_case_diagram-user.plantuml
```

## Catatan

- Simpan file sumber (`.d2` / `.plantuml`) sebagai acuan utama.
- Gunakan penamaan file konsisten sesuai domain proses agar mudah ditelusuri.
