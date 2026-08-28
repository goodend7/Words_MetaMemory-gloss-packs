# Gloss packs (작업 디렉터리)

파일명: `en_{mother}_dict.txt`, `en_{mother}_idioms.txt` (예: `ko/en_ko_dict.txt`, `ja/en_ja_dict.txt`)

빌드 스크립트 출력 위치입니다. **공개 배포**는 sibling repo [`Words_MetaMemory-gloss-packs`](../Words_MetaMemory-gloss-packs/) (GitHub public)로 push합니다.

- manifest URL: `https://raw.githubusercontent.com/goodend7/Words_MetaMemory-gloss-packs/main/manifest.json`
- 동기화: `python c:\1PY\eng_dict\build_gloss_packs.py --sync-ko --manifest-only`
