# Practice_List
## bookmark
- github 소스 -> Pycharm 프로젝트
- bookmark 앱 만들기
- models Bookmark 만들기
- admin Bookmark 등록하기
- python manage.py makemigrations bookmark
- python manage.py migrate
- python manage.py createsuperuser
- models Bookmark __str__() 출력하는 문구 설정
- urls bookmark:list
- views BookmarkList
- templates bookmark_list.hrml
- views BookmarkCreateView
- templates bookmark_create
- urls add
- modify bookmark_list Add Bookmark link
- views BookmarkDetailView
- templates bookmark_detail
- urls detail/<int:pk>/
- modify bookmark_list detail link
- update: views BookmarkUpdateView, templates bookmark_update.html, urls, modify Modify link
- delete: views BookmarkDeleteView, templates bookmark_confirm_delete.html, urls, modify Modify link
- Cancel button 만들기, base.html 확장하기, bootstrap 적용하기
- pagination view, base.html, bookmark_list.html