# paraview tutorial
### ParaView 설치
- ParaView 설치 명령
```
$ flatpak install flathub org.paraview.ParaView
```
#### flatpak이 없다고 한다면,
```
$ sudo apt install flatpak
```
- 재부팅
```
$ sudo reboot
```
- 다시 설치 명령
```
$ flatpak install flathub org.paraview.ParaView
```

#### 오류 발생
- 오류 메세지  
```
no remote refs found similar to 'flathub'
```
 - 해결 방법
```
$ flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
깔끔~
- 다시 설치 명령
```
$ flatpak install flathub org.paraview.ParaView
```

#### ParaView 실행
```
$ flatpak run org.paraview.ParaView
```
