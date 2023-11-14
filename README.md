# dstoolbox-2-66-64114540366
private project for ds toolbox class

## 07/11/2566

- ติดตั้ง scoop.sh

- ติดตั้ง github-cli

        scopp install git   
        scoop bucket add main
        scoop install gh

- สร้างสภาพแวดล้อมใหม่

        python -m venv venv
        ..\venv\Scripts\activate

- ติดตั้ง package

        pip install django

## 14/11/2566
- สร้าง github resposity ของตัวเอง

        Username/dstoolbox-2-66-66xxxxxxxxx

- เพิ่ม wichit2s เป็น collaborator

- การเข้าใช้งาน github

        gh auth login
        gh repo clone FiFiee19/dstoolbox-2-66-64114540366

- เริ่มเขียน markdown

[การเขียนเอกสารบน Github]
(https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- github.com/cookiecutter/cookiecutter-django


        venv\Scripts\activate
        pip install django pre-commit
        pip install cookiecutter
        cookiecutter gh:cookiecutter/cookiecutter-django

drf = django rest framework