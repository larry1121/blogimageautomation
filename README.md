# blogimageautomation

이 파이썬 스크립트는 블로그 포스트용 대문 이미지를 생성합니다. 포스트 제목과 블로그 이름을 커스터마이징하여 만든 이미지는 블로그 포스트의 멋진 커버 이미지로 사용할 수 있습니다.

![생성된 이미지](https://github.com/larry1121/blogimageautomation/assets/78005200/bd6cce5a-d171-4cd4-8cd8-0957aee7caa3)


## requirements

- Python 3.x
- Pillow 9.5.0
- 원하는 폰트의 .ttf 파일

## How to use

1. 시스템에 Python 3.x가 설치되어 있는지 확인하세요.
2. 아래 명령을 사용하여 필요한 라이브러리를 설치하세요:
pip3 install Pillow==9.5.0
3. `"PATH_OF_THE_FONT.ttf"`를 원하는 폰트 파일의 실제 경로로 대체하세요 (TrueType 폰트).
4. 다음 파라미터를 선호에 맞게 조정하여 스크립트를 커스터마이징하세요:
- `size`: 생성된 이미지의 크기 (가로, 세로).
- `background_color`: 이미지의 배경색.
- `min_font_size`: 포스트 제목의 최소 폰트 크기.
- `max_font_size`: 포스트 제목의 최대 폰트 크기.
- `blog_name`: 블로그 이름.
- `post_title`: 블로그 포스트의 제목.
- `text_color`: 텍스트의 색상.
- `border_color`: 테두리의 색상.
- `border_width`: 테두리의 너비.
5. 다음 명령을 사용하여 스크립트를 실행하세요:
python blogTitleImageAuto.py
6. 생성된 이미지는 `images` 디렉토리에 포스트 제목을 파일명으로 하여 저장됩니다.

## Example

블로그 이름이 "내 기술 블로그"이고 포스트 제목이 "파이썬 시작하기"일 경우, 다음과 같이 파라미터를 설정할 수 있습니다:

```python
blog_name = "내 기술 블로그"
post_title = "파이썬 시작하기"
```
## Generated image
생성된 이미지에는 지정한 블로그 이름과 포스트 제목이 색상이 지정된 배경 위에 가운데 정렬되어 있습니다. 이미지에는 시각적 효과를 위해 하얀색 테두리가 포함되어 있습니다.

![생성된 이미지](https://github.com/larry1121/blogimageautomation/assets/78005200/bd6cce5a-d171-4cd4-8cd8-0957aee7caa3)



## 참고 사항
필요한 폰트 파일 (TrueType 폰트)이 지정한 경로에 있는지 확인하세요.
스크립트는 포스트 제목을 이미지 너비 내에 맞도록 폰트 크기를 조정합니다.
이 스크립트를 필요에 맞게 수정하고 변경하여 사용해보세요!
