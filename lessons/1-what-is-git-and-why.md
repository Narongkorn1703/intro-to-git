## Git คืออะไร 👨🏽‍✈️

Git คือ เครื่องมือที่เอาไว้ใช้จัดการเกี่ยวกับการควบคุม version ของ software **(Version Control System)**

Git ทำหน้าที่ในการ **track การเปลี่ยนแปลงของไฟล์โค้ดของเรา** ว่าใครทำการแก้ไขไฟล์อะไร และเมื่อไหร่ ซึ่งการเปลี่ยนแปลงพวกนี้จะถูกเก็บไว้เป็น record history ในเครื่องคอมพิวเตอร์ของเราเอง

และ **Git ยังทำให้เราทำงานเป็นทีมได้ง่ายขึ้นเวลาเขียนโค้ดด้วยกัน** ลองนึกภาพว่า เวลาเราทำงานเป็นทีม เราต่างคนต่างแก้โค้ดในไฟล์ต่าง ๆ เวลาเอามารวมกันเราจะรวมกันยังไงดีหล่ะ แน่นอนว่า Git เกิดมาแก้ไขปัญหาตรงจุดนี้ได้อย่างดีซึ่งเดี๋ยวเราจะดูกันต่อไป

### ก่อนจะไปต่อเรามา Setup กันสักนิดหน่อย

1. ให้เราไปที่ [git-scm.com](https://git-scm.com/downloads) เพื่อ Download Git ลงมาบนเครื่องเราก่อน

2. ถ้า Download เสร็จแล้วให้เข้าไปที่ CMD หรือ Terminal ของเครื่อง Computer ของเรา แล้วทำการพิมพ์ `git` ถ้าหน้าจอขึ้นข้อความประมาณในรูปคือ Install เสร็จเรียบร้อยละ

```
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout
   
...
```

