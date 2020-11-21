Embed Bot
===

##config.json 파일 셋팅 및 공지 내용 변경하는법.##
===
token - 이 부분엔 봇의 토큰을 입력해 주세요. 
https://discord.com/developers/applications 이 링크로 들어가 'New Application' 을 통해 어플리케이션을 만든 후 
bot 으로 가셔서 Add Bot 을 누르시면 복사가 가능한 토큰을 얻으실 수 있습니다.

msg1, msg3, msg5 는 내용의 제목을 써 넣으시면 됩니다.
```ex) "msg1": "수정사항",```

msg2, msg4, msg6 에는 내용을 적어주세요.
```ex) "msg2": "이번의 변경사항은 OOOOOOOO(이)가 수정되었습니다.",```

col 이 부분에는 헥사코드를 입력해 주세요.\n
ex) "col": "#7fffd4",\n
\n
"title" 에는 쓰고 싶으신 공지의 제목을 적어주세요. \n
위의 msg들과 똑같이 쓰면되기에 따로 예시를 두지 않았습니다.\n

prefix - 명령어의 접두사에 해당됩니다.
---------------------------------------------------------- 주의 ---------------------------------------------------------------------------
prefix는 맨 마지막 줄이므로 끝에 붙는 ' , ' 표시가 붙지 않습니다! 만일 붙일경우 에러가 발생합니다.\n
```ex) "prefix": "."\n```

**해당 내용은 가이드.txt 에도 들어가 있습니다!**
---------------------------------------------------------- 전체 예시 ---------------------------------------------------------------------------

```
{
    "token": "봇토큰",\n
    "msg1": "이곳은 첫번째 내용의 제목",\n
    "msg2": "이곳은 첫번째 내용",\n
    "msg3": "이곳은 두번째 내용의 제목",\n
    "msg4": "이곳은 두번째 내용",\n
    "msg5": "이곳은 세번째 내용의 제목",\n
    "msg6": "이곳은 세번째 내용",\n
    "col": "#7fffd4",\n
    "title": "임베드의 전체 제목부분",\n
    "prefix": "."\n
}```
