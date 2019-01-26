---
---

# ي : لغة البرمجة


**_Ya (ي)_** is an open source programming language where you can write python code in arabic language.

It takes the arabic text and convert it into python code and execute it. 
Which then can be used anywhere. You can code anything which you can code in python.

> It is recommended to use [IntelliJ IDEA](https://www.jetbrains.com/idea/) as it support RTL text direction and and it also support .ي extension. 

> **You can add [IntelliJ plugin for Ya Language](https://plugins.jetbrains.com/plugin/11321-ya---language).**
For installing pluging search 'ي' keyword in plugin tab of intelliJ editor.

- **Hello World** [Sample File اهلا.ي](https://github.com/yalang/examples/blob/master/اهلا.ي)
```python
اطبع("اهلا و سهلا يا عالم")؛
```
Output:
```bash
اهلا و سهلا يا عالم
```

- **Condition** [Sample File لو.ي](https://github.com/yalang/examples/blob/master/لو.ي)
```python
ع = ٧
لو ع ٪ ٢ == ٠:؛
    اطبع("ع الفردية")؛
ولو ٧ == ٠:؛
    اطبع("هذا صفر")؛
اخر:؛
    اطبع("ع الزوجية")؛
```
Output:
```bash
ع الزوجية
```

- **Function** [Sample File وظيفة.ي](https://github.com/yalang/examples/blob/master/وظيفة.ي)

```python
وظيفة جمع(اولا، ثاني):؛
    كل = اولا + ثاني؛
    ارجع كل؛

اطبع("جمع = "، جمع(٢، ٣))؛
```
Output:
```bash
جمع =  ٥
```

**NOTE: `؛` is optional at the end of line**



For more sample code see (https://github.com/yalang/examples)


## Prerequisites
- Mac OS or Ubuntu
- Python 3


## Getting Started
### Installation
- Clone this repo:
```bash
git clone https://github.com/yalang/ya.git
cd ya
```
- Run install.sh:
```bash
./install.sh
```

- Or run Makefile:
```bash
make install
```

## Running

- Create a new file with name `اهلا.ي` and open in any editor.

- Write this in the file

```vim
اطبع("اهلا و سهلا يا عالم")؛
```

- Save it

- Open a terminal and go to the folder where file is saved

- Run this command

```bash
ي اهلا
```

- It will print 

```bash
اهلا و سهلا يا عالم
```
