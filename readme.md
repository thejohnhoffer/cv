### Compile to HTML instead of PDF

```
htxelatex main.tex

mv main.html docs/john-hoffer/spring-2018/harvard-seas/computer-graphics-connectomics.html
mv *.png docs/john-hoffer/spring-2018/harvard-seas/
rm main-1.svg
rm main.css

git apply diff/svg-1.diff
```

