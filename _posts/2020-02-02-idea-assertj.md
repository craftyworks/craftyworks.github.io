---
title: "IntelliJ IDEA 에서 assertj 사용 편하게 하기"
excerpt: "assertThat 사용시 import static 깔끔하게 적용하는 방법"

categories: 
  - IT
tag:
  - assertj
  - junit
  - IDEA
last-modified-at: 2020-02-02T00:52:00
---

## Settings

* Editor > Code Style > Java
    * Imports Tab    
    ```
    Names count to use static import with '*' : 1
    ```

## static import

1. `assertThat` 입력 후 `Ctrl+Alt+Space` 클릭
1. `Assertions.assertThat` 선택 상태에서 `Alt+Enter` 클릭 
1. `Import Statically` 선택


