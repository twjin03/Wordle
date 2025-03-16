# Wordle 

이 프로젝트는 HTML, CSS, JavaScript를 활용하여 Wordle 게임을 구현한 것입니다.


## 📥 다운로드 및 실행 방법

### 1. 프로젝트 파일 다운로드 방법

아래 두 가지 방법 중 하나를 선택하여 프로젝트를 다운로드 해주시기 바랍니다.

#### (1) ZIP 파일 다운로드
    "Wordle.zip" 압축 파일을 직접 다운로드

#### (2) Git을 이용

```sh
git clone https://github.com/twjin03/Wordle.git
cd Wordle 
```
---

### 2. 실행 방법
아래 두 가지 방법 중 하나를 선택하여 프로젝트를 실행 해주시기 바랍니다.

#### (1) VS Code에서 실행

1. Visual Studio Code를 열고 **파일 > 폴더 열기**를 선택하여 `Wordle` 폴더를 엽니다.
2. **Live Server 확장 프로그램**을 설치합니다.
3. `index.html` 파일을 열고 마우스 오른쪽 버튼을 클릭하여 "Open with Live Server"를 선택합니다.
4. 브라우저에서 자동으로 실행됩니다.

#### (2) 웹 사이트 주소를 통해 접속

아래 주소를 통해 사이트에 접속해주세요.

https://twjin03.github.io/Wordle/

---

## 🎮 게임 설명

1. **게임 시작/재시작 버튼**: "Start(Restart) Game" 버튼을 통해 정답 단어를 초기화하고 게임을 시작할 수 있습니다. 게임이 시작되면 화면에 5x6 격자(word grid)가 나타납니다.

2. **단어 입력 및 제출**: 키보드 또는 가상 키보드 버튼을 이용하여 단어를 입력할 수 있습니다. 

    정답 단어를 유추하여 입력해보세요! (기회는 6번이며, 모든 시도 후 정답을 맞히지 못하면 자동으로 게임이 종료되고 재시작됩니다.)

3. **입력 결과 표시**:
   - 💚초록색💚: 정확한 위치에 있는 글자를 맞혔을 경우
   - 💛노란색💛: 정답 단어에 포함되지만 위치가 틀린 글자인 경우
   - 🩶회색🩶: 정답 단어에 포함되지 않는 글자인 경우

4. **애니메이션 효과**: 
- 입력 시 박스 pop 효과
- 결과 색을 표시할 시 flip 효과
- 입력 글자 수 부족 또는 유효하지 않은 단어일 경우 shake 효과
- 정답 단어 5글자를 모두 맞힐 경우 jump 효과
---

## 📌 주요 파일 설명

- `index.html` : 게임의 기본 구조를 구성하는 HTML 파일
- `style.css` : UI 및 애니메이션을 담당하는 CSS 파일
- `index.js` : 게임 로직이 포함된 JavaScript 파일
- `words.js` : 사용 가능한 단어 목록이 포함된 파일

\* 구체적인 구현 로직은 파일 내용을 확인해주시기 바랍니다.

---

\* 게임 시작 후 'Ctrl' + 'Shift' + 'I' 키를 통해 개발자 도구 실행, 콘솔 창을 확인하여 설정된 정답 단어를 확인할 수 있습니다. 
