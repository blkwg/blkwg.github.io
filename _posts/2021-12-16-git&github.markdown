---
layout: post
title:  "git과 github"
date:   2021-12-16
categories: None
---
git은 여러 명이서 한 코드를 관리하는, 즉 협업을 할 때 쓰이는 분산 버전관리 시스템이다.
github는 git을 활용한 대표적인 원격 저장소로, 전 세계 사람들과 협업을 할 수 있다.

{% highlight ruby %}
git init
//현재 디렉토리를 git 저장소로 지정함.
git status
//현재 git 상태 확인. 변경된 사항이 있는 파일 표시.
git add <filename>
//깃허브에 올릴 변경사항을 추가한다.
git commit -m "msg"
//변경사항을 저장. msg에 코멘트를 남길 수 있다.
git branch <branch_name>
//새로운 브랜치 생성
git checkout <branch_name>
//branch_name 브랜치로 이동.
git merge <branch_name>
//현재 작업중인 branch를 원하는 branch에 병합
{% endhighlight %}

{% highlight ruby %}
git clone <repo_url>
//깃과 깃허브와 연결한다.
git push
//깃허브에 푸쉬한다==깃허브에 올린다.
{% endhighlight %}




[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
