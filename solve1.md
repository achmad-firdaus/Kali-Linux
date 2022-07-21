
### This sample Error if you are update kali linux:
![image](https://user-images.githubusercontent.com/77251566/180193779-6c0bdecd-b752-4d20-9824-3b61285f73a1.png)

### How to solve:
  - First
    - Visit this Link http://http.kali.org/kali/pool/main/k/kali-archive-keyring/ and you can see this list in year 2022
    - ![image](https://user-images.githubusercontent.com/77251566/180194459-bb873965-2241-4f7f-8253-a7a582acc42a.png)
    - You can choose: kali-archive-keyring_XXXX.1_all.deb
    - In year 2022, i can do this in the terminal: sudo wget --no-check-certificate http://http.kali.org/kali/pool/main/k/kali-archive-keyring/kali-archive-keyring_2022.1_all.deb
    - install: sudo apt install ./kali-archive-keyring_2022.1_all.deb
    - sudo apt update && apt upgrade && apt dist-upgrade
    - SOLVE! ThankYou.
