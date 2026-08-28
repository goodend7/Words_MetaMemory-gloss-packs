# Words MetaMemory — Gloss Packs (Public)

영어 학습 확장 [Words_MetaMemory](https://github.com/goodend7/Words_MetaMemory) (private)용 **오프라인 뜻 사전** 데이터만 공개합니다.

확장 소스는 private repo에 두고, 이 repo에는 `en_dict.txt` / `en_idioms.txt` / `manifest.json` 만 포함합니다.

## 구조

```
manifest.json
ko/en_dict.txt
ko/en_idioms.txt
{lang}/...   # full 재빌드 후 추가
```

## manifest

`https://raw.githubusercontent.com/goodend7/Words_MetaMemory-gloss-packs/main/manifest.json`

## 갱신 (maintainer)

private repo에서 빌드 후 이 repo로 복사·push:

```powershell
cd c:\1PY\eng_dict
python build_gloss_packs.py --sync-ko --manifest-only
# gloss-packs/ 내용을 이 repo 루트에 복사 후 commit & push
```
