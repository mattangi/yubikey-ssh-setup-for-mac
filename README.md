# Mac OS 에서의 Yubikey로 ssh authentication (openpgp를 사용 한 방법)
세팅은 다음의 순서로 진행 됩니다.  로컬호스트는 맥어에스로 가정합니다.  리모트호스트는 openssh를 사용하는 macos, linux...  linux가 로컬호스트일때도 방법은 동일하지만 scdaemon pcscd를 추가적으로 설치해야 함.
1. Localhost에 gnupg 설치.  (gui frontend optional.  Kleopatra. algertc/kleopatra4mac/kleopatra.)
2. Yubikey에 openpgp app을 사용해서 key를 생성하고 authentication certificate을 만든다.  4096bit key를 생성하기 위해 Yubikey 4 혹은 Yubikey 5로 진행.
3. 
