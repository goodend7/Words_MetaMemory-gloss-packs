# Public repo 최초 배포 (1회)

GitHub에 **빈 public 저장소**를 만든 뒤 push합니다.

## 1. 저장소 생성

브라우저에서 (goodend7 계정):

https://github.com/new?name=Words_MetaMemory-gloss-packs&visibility=public&description=Public+gloss+packs+for+Words+MetaMemory

- **Add a README** 등은 체크하지 않음 (이미 로컬에 있음)
- **Create repository** 클릭

## 2. push

```powershell
cd c:\1PY\Words_MetaMemory-gloss-packs
git push -u origin main
```

## 이후 갱신

```powershell
cd c:\1PY\eng_dict
python build_gloss_packs.py --publish-public
cd c:\1PY\Words_MetaMemory-gloss-packs
git add .
git commit -m "Update gloss packs"
git push
```
