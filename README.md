# Awesome Latex CV 中文版


+ 该分支包含所有文件，**包括中文字体**，文件比较大

## 示例
+ 点击下载 [PDF](http://oxuze83b3.bkt.clouddn.com/CV/pdf/CV_zh.pdf) 示例。
## 编译

+  采用 `xelatex` 编译。
+  需要 [fontawesome Package version 4.6.3.2.](http://www.ctan.org/tex-archive/fonts/fontawesome) 或更高版本（已经放在仓库的主目录下）。
+  中文支持借鉴[billryan/resume/tree/zh_CN的中文分支](https://github.com/billryan/resume/tree/zh_CN),`zh_cn-adobefonts_external.sty`,`zh_cn-adobefonts_internal.sty`和adobe字体库(在`fonts/zh_cn-adobe/`目录下,56.4MB)都来自于该仓库分支，感谢分享。



## The Latex 文件结构

```matlab
% cls file
awesome-source-cv.cls   

% main file 主函数
CV_zh.tex

%subsection
  - section_headline.tex
  - section_education.tex
  - section_publications.tex
  - section_skills.tex
  - section_experience_short.tex
  - section_languages.tex
  - section_awards.tex
  - section_interests.tex
```

## License

The LaTeX Project Public License