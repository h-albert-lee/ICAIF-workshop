# Kiii Kiii — ICAIF'26 Workshop paper (Overleaf-synced)

- 본문 원본은 **Overleaf**. 이 레포는 Overleaf GitHub 연동 대상이며, 연구 레포 `kiii-kiii-workspace`의 `paper/` submodule 입니다.
- `main.tex` → `sections/*.tex`. 제출 모드 `\documentclass[sigconf,anonymous,review]{acmart}`; 카메라레디는 `[sigconf]` + `\anonymousfalse`.
- `references.bib`·`figures/*.pdf`는 연구 레포의 `literature/papers.bib`·`figures/out/`에서 `scripts/sync_figures.sh`로 복사됩니다. **여기서 직접 고치지 마세요.**
- 컴파일: kotex 사용 → Overleaf 컴파일러를 XeLaTeX 또는 LuaLaTeX로.
- 타겟: Workshop on Financial AI Security, Privacy, and Safety @ ICAIF'26 — 4 pages excl. refs, double-blind, 마감 2026-10-08 (AoE 가정).
- acmart 샘플(`sigconf*.tex`, `sample-*.bib`, `acmguide.pdf`)은 참고용으로 남겨둠.
