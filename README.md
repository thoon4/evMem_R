# Research Project : Stability of background context promotes the binding of multiple event memory

## Index
  - [Authors](#authors) 
  - [About](#about) 
  - [Overview](#overview) 
  - [Files](#files)
  - [License](#license)

## Authors
- **Taehoon Kim**, & Ghootae Kim
- Deep Memory Lab, Cognitive Science Research Group, Korea Brain Research Institute

## About
- 이 Repository는 KBRI, 인지과학 연구그룹, 심층기억연구실에서 2020에 수행한 행동 인지 실험의 데이터 분석 작업물을 담고 있습니다.
- 실험 프로그램 코드, 개별 참가자의 원본 데이터는 포함되어 있지 않습니다. 
- 분석은 R과 R studio를 통해 수행되었으며, 분석 코드 및 결과는 **evMem_Results.html** 를 다운로드받아서 확인할 수 있습니다. 
- 다른 파일에 대한 정보는 아래 **FILES**에서 확인할 수 있습니다.

## Overview
- Event Memory 형성 과정에서 Hierarchical Background Context와 Prior Experience / Expectation 의 효과를 검증
- 연속적인 경험은 Event Boundary 에 의해 분할되어 여러 Event Memory로 부호화, 통합된 Event Memory 내에서는 사건 간의 Temporal Order Memory가 온전한 반면, 분리된 Event Memory 간에는 Temporal Order Memory 가 손상된다.
- Prior Experience / Expectation은 Event stream에 대한 안정적 context를 제공해주어, prior experience와 일치하게 흐르는 event memory를 통합할 수 있다. 반면, prior experience과 불일치하게 흐르는 event memory는 서로 강하게 분할될 수 있다. 이러한 효과는 Temporal Order Memory에 반열될 수 있다.
- 두 단계 행동 실험 진행. 단계 1 - 사전 경험 형성, 단계 2 - 배경 맥락 하에서의 Event Memory 형성 및 Temporal Order Memory 검사. Prior Experience와 Event Stream 간 일치, 불일치 여부 확인.
- 일치 조건과 불일치 조건 비교 결과. 일치 조건에서 Across-Event Temporal Order Memory가 더 우수. 서로 다른 배경 맥락임에도 불구하고 Prior Experience와 일치하는 경우에 Event Integration 확인.


## Files
- evMem_Results.Rmd : 데이터 분석을 위한 RMarkDown source code
- evMem_Results.html : 분석 코드 및 결과, 다운로드 후 확인 가능
- data : raw data 폴더, 비어있음
- image : 결과 요약 관련 이미지
- KBRI2021.evMem.R.thk.pdf : 프로젝트 관련 로그

## License

```
MIT License

Copyright (c) 2020 Kim, Taehoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
