# Discord.py Docs 한글화 프로젝트

> [문서 링크](https://discordpy-ko.github.io/)  
이곳에서는 로케일 파일만 올립니다.  

중복된 문서가 번역되는 것을 방지하기 위하여, 하단에 명시된 디스코드 서버로 접속하여 번역 진행 상황과 예정 등을 확인해주세요. 또, 문서 업데이트는 디스코드 서버에 있는 봇을 통해서만 가능합니다.

## 목차

- [기여방법](#기여방법)
- [도움](#도움)
- [(옵션) 번역 테스트 방법](#(옵션) 번역 테스트 방법)

## 기여방법

1. 이 리포지토리를 포크해주세요.  

2. 텍스트 에디터를 이용해서 .po 파일들을 열고 번역을 진행해주세요. 이때 번역된 내용은 `msgstr`에 넣어야 합니다.  

3. [Pull Request](https://github.com/discordpy-ko/discord.py-docs-kor-project/pulls)에 변경한 파일 리스트를 함께 적어서 올려주세요. (쉬운 검수를 위함입니다.)  

## 도움

번역을 순조롭게 진행하기 위해 [디스코드 서버](https://discord.gg/YbfbxpX)를 생성하였습니다.

## (옵션) 번역 테스트 방법

1. [이곳](https://github.com/Rapptz/discord.py)에서 이 리포지토리를 클론해주세요. (docs 폴더를 이용해서 바로 테스트 가능)

2. ``pip install sphinx``, ``pip install sphinx-intl``를 통해 `sphinx` 라이브러리를 설치하고 html로 변환을 준비해주세요.  

3. [이곳](http://www.sphinx-doc.org/en/master/usage/advanced/intl.html)을 참고해서 html로 변환해서 테스트를 진행해주세요.  
