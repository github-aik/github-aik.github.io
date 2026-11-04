/demo 页截图。页面引用 *.webp（见 landing/data/mock.ts）。

换图：覆盖同名 .webp，或放入同名 .png 后在本目录执行：
  for f in *.png; do cwebp -q 78 -m 6 "$f" -o "${f%.png}.webp"; done

文件名：path-01 path-02 gui-01-menu … gui-06-local-dev
