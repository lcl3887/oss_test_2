# oss_test_2
oss_test_2

## 1 Add quotes to ansible playbook
` $ vimgolf put 5f0f5fbe280fbf000c23330 `

- 최고점 : 8

- 나의 점수 :9

![test1](https://user-images.githubusercontent.com/77104243/144735191-4748624c-ddf2-4b26-880c-823048bffdf2.gif)

G : 파일의 마지막 줄로 이동

W : 다음 단어 시작으로 이동

i : insert로 전환

" 입력

End : 문장 끝으로 이동

" 입력

<Esc> ZZ : 저장
  
  
## 2 simple replacements
`$ vimgolf put 603ba26a01b4d00009c10a49`

- 최고점 : 19

- 나의 점수 : 27
  
![test2](https://user-images.githubusercontent.com/77104243/144735619-17a46dd5-98f4-422d-9cdc-a2b044f0aa8e.gif)

:4 :4행으로 이동
  
O : 위 행이 만들어지면서 insert모드로 전환
  
// C-N(Ctrl+N) TODO 입력
  
gg :파일의 첫 줄로 이동
  
:6 :6행으로 이동
  
O
  
// C-N TODO
  
<Esc>
  
ZZ
  
  
  
## 3 Satisfy the go linter
`$ vimgolf put 5f1063aa8361810006e73210`

- 최고점 : 20

- 나의 점수 : 30
  
![test3](https://user-images.githubusercontent.com/77104243/144736129-bef02bf0-47a4-4d24-b370-f0f74fb2979d.gif)


:4 :4행으로 이동

O : 행이 만들어지면서 insert모드로 전환

// C-N(Ctrl+N) TODO 입력

<Esc>

:6 :6행으로 이동
  
O :행이 만들어지면서 insert모드로 전환
  
// C-N TODO 입력
  
<Esc>
  
ZZ
  

  
  
## 4 Plotting some variables in python
`$ vimgolf put 9v0060da5177000000000209`

- 최고점 : 34

- 나의 점수 : 69
  
![test4](https://user-images.githubusercontent.com/77104243/144735622-05853144-d69d-4b46-bf69-d0cb5e47e493.gif)

:%s/y1/abs(y1)/g :y1을 abs(y1)으로 변경
  
gg : 파일의 첫 줄로 이동
  
/1<CR> : 1검색
  
nnn :정방향으로 검색 반복 3번

r2nr2nr2n :한글자를 2로 바꿈 3번
  
r3nr3nr3n : 3으로 바꿈 3번
  
r4nr4nr4n : 4로 바꿈 3번
  
gg :파일의 첫 줄로 이동
  
/k<CR> : k검색
  
n :정방향으로 한번 이동
  
rbn :b로 바꾸고 이동
  
rrn :r로 바꾸고 이동
  
rgn :g로 바꾸고 이동
  
ZZ 


  
  
  
## 5 Python dataclasses
`$ vimgolf put 6013804df3308e0009368f1c`

- 최고점 : 19

- 나의 점수 : 41
  
![test5](https://user-images.githubusercontent.com/77104243/144735626-73476e92-1fb9-48c2-882f-19a48aebf8a9.gif)

G : 파일의 

Backspace
  
C-N으로 단어 검색 후 , 입력 을 반복
  
<Esc>
   
ZZ

