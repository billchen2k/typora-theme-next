# NexT for Typora

![image-20200423021248443](https://billc.oss-cn-shanghai.aliyuncs.com/img/2020-04-23-image-20200423021248443.png)

<p align="center">🖋 An elegant and simple Typora theme, inpired by Hexo theme <a href = 'https://github.com/theme-next/hexo-theme-next'>NexT</a>.
    <br /><img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/BillChen2K/typora-theme-next/total?style=flat">  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/BillChen2K/typora-theme-next"></p>

## Features

English 🇺🇸 & 中文 🇨🇳 supported, `JetBrains Mono` as mono font. 

NexT is one of the most powerful and elegant themes for hexo. This is a transplanted version of NexT on Typora, with English font `Overpass` and Chinese font `Glow Sans` ([未来荧黑](https://github.com/welai/glow-sans))，a modern and concise Chinese font by Zhejiang University.

This theme includes styles for typos, underline, checkbox and sidebar, and a Helvetica version for fans of classic fonts. Tuned for both macOS and Windows, and now with a dark version:

![image-20200529142243531](https://billc.oss-cn-shanghai.aliyuncs.com/img/2020-05-29-yvVEHP.png)

## Usage

There will be four css files, drag whichever css file you like <u>& next folder</u> to your Typora theme folder and restart Typora.

Helvetica font would look more constraint and academic. For fans of Helvetica, both light and dark theme have a Helvetica version. Note that line height in Helvetica version is slightly tightened for better appearance.

Code [ligatures](https://www.jetbrains.com/lp/mono/)  in JetBrains Mono are disabled by default. If you want it on, just find  `font-variant-ligatures: none;` in the css files and comment that line.

If you want to change the font size of exported files (like pdf or docx), edit `export-font-size` variable in the css files.

## Example

Inline styles support **strong**, *Emphasis*, `code`, <u>underline</u>, ~~strikethrough~~, $\LaTeX$, X^2^, H~2~O, ==highlight==, [Link](typora.io), and emoji😉。

- With fully Chinese support：使用未来荧黑字体显示中文文字。
  
  - 中文字体排版效果是什么样子？要解决这个问题，首先需要随便准备一些简体汉字，然后把他们放在这里，再啰嗦几句。
- And an elegant English font: Overpass.
- Everybody loves `JetBrains Mono`.
- [x] Check box styled.

```c
#include <iostream>
int main(){
  std::cout << "Hello World!" << end;
}
```

| Table | Style | Of   | NexT |
| ----- | ----- | ---- | ---- |
| Is    | Shown | Here | .    |

## Notes

> Glow Sans font would look better on HiDPI screens. If you don’t have one and had a bad experience, you can delete Glow Sans font under the `next` folder and it will use your Microsoft YaHei or PingFang to render Chinese. 

Author: Bill Chen ([https://billc.io](https://billc.io)) ⛵️

2020.4