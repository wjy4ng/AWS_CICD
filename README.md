# AWS + GIT + GITHUB + GIT ACTION + AWS Developer Q + SageMaker + Bedrock

## SSH 키 생성
```
# 내 PC에 ssh 키 생성
ssh-keygen -t rsa -C "xxx@xxx.com"

# 내 웹 github 설정에서 공개키 등록
cat ~/.ssh/id-rsa.pub

# push 하면 매번 passphrase(암호)를 입력해야하므로 Mac에 키체인 저장
ssh-add --apple-use-keychain ~/.ssh/id_rsa
```