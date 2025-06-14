# DH-Buddhist-Analysis-Tutorial (파이썬으로 시작하는 디지털 인문학 불교 텍스트 분석 튜토리얼)

이 레포지토리는 디지털 인문학에 관심 있는 분들을 위한 불교 텍스트 분석 튜토리얼 공간입니다. 코딩 경험이 많지 않은 인문학 연구자나 학생들이 파이썬을 활용하여 불교 텍스트를 직접 분석하고 연구에 적용할 수 있도록 돕는 것을 목표로 합니다. 기초적인 Bag-of-Words(BoW) 모델부터 시작하여 점차 다양한 텍스트 분석 기법을 다룰 예정입니다. 

Welcome! This repository is designed for humanities scholars, students, and enthusiasts who want to explore Buddhist texts using computational methods. Our goal is to provide a gentle introduction to text analysis with Python, even if you have little to no prior programming experience. We start with the fundamentals, such as the Bag-of-Words (BoW) model, and will gradually build up to more advanced techniques. 

본 튜토리얼은 2025년 6월 1일에 시작된 불교 텍스트 분석 모임에서 함께 만들어가고 있습니다. 이 모임에 관심 있으신 분은 songi113@hanmail.net으로 이메일 주세요! (그 외에 해당 튜토리얼의 보완해야 될 점, 추가했으면 하는 부분 등 편하게 메일 주세요)

We're actively building this tutorial alongside the Buddhist Text Analysis Meeting, which commenced on June 1, 2025. If you're interested in joining our group, please email us at songi113@hanmail.net!

---

💻 튜토리얼 실습 방법 (How to Use This Tutorial)
이 튜토리얼은 Google Colab 환경에서 직접 코드를 실행하며 학습하도록 만들어졌습니다. GitHub에 처음 오신 분들도 아래 단계를 따라 하시면 누구나 쉽게 실습에 참여할 수 있습니다.

This tutorial is designed for hands-on learning by running code directly in the Google Colab environment. Even if you're new to GitHub, you can easily participate by following the steps below.

시작 전 준비물: Google 계정 (A Google Account is required.)

1단계: 실습 파일(Colab 노트) 찾기 (Step 1: Find the Tutorial File)
📂 이 페이지(레포지토리)에서 아래로 스크롤하거나 파일 목록을 살펴보면, 파일 이름이 .ipynb로 끝나는 파일들이 있습니다. 이것이 바로 우리가 실습할 Colab 노트입니다.

1_파이썬과_데이터구조_기초.ipynb
2_파이썬과_DH데이터전처리.ipynb
(이후 튜토리얼 파일들...)
On this repository page, scroll down or look at the file list. You will find files ending with the .ipynb extension. These are the Colab notebooks for our tutorial.

2단계: Colab에서 파일 열기 (Step 2: Open the File in Colab)
🖱️ 원하는 튜토리얼 .ipynb 파일을 클릭하세요. 파일 내용이 보이면, 페이지 상단에 있는 "Open in Colab" 배지(버튼)를 클릭합니다.

Click on the .ipynb file you wish to start. Once you see the content of the file, click on the "Open in Colab" badge/button located at the top of the page.

3단계: 내 드라이브에 사본 저장하기 (Step 3: Save a Copy to Your Drive) - [매우 중요!]
✨ Colab으로 파일이 열리면, 가장 먼저 자신만의 복사본을 만들어야 합니다. 이렇게 해야 자유롭게 코드를 수정하고 실행 결과를 저장할 수 있습니다.

메뉴에서 **파일 (File) -> Drive에 사본 저장 (Save a copy in Drive)**을 클릭하세요.

Once the file opens in Colab, the very first thing you should do is create your own copy. This allows you to freely edit the code and save your results.

In the menu, click on File -> Save a copy in Drive. A new tab will open with your personal copy of the notebook.

4. 단계: 코드 실행하며 실습하기 (Step 4: Run the Code and Practice)
▶️ 이제 선생님만의 튜토리얼 노트가 생겼습니다. Colab 노트는 '셀(Cell)'이라는 블록 단위로 구성되어 있습니다.

코드 셀 실행: 실행하고 싶은 코드 셀을 마우스로 클릭한 후, 셀 왼쪽에 나타나는 **'재생' 버튼(▶️)**을 누르거나, 키보드에서 Shift + Enter 키를 동시에 누르면 됩니다.
순서대로 실행: 특별한 안내가 없다면, 노트북의 가장 위쪽 셀부터 순서대로 실행하며 설명을 읽고 결과를 확인하는 것이 가장 좋습니다.
You now have your own tutorial notebook! A Colab notebook is made up of blocks called 'cells'.

To run a code cell: Click on the cell you want to run, and then either press the 'Play' button (▶️) that appears to the left of the cell, or press Shift + Enter on your keyboard.
Run cells in order: For the best experience, it is recommended to run the cells sequentially from the top of the notebook to the bottom.

💡 궁금한 점이 있다면?
언제든 songi113@hanmail.net으로 편하게 질문해주세요!
