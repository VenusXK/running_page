```shell
python run_page/gen_svg.py --from-db --title "运动热力图" --type github --athlete "景赫" --special-distance 10 --special-distance2 20 --special-color yellow --special-color2 red --output assets/github.svg --use-localtime --min-distance 0.5
```

```shell
python run_page/gen_svg.py --from-db --title "运动轨迹图" --type grid --athlete "景赫"  --output assets/grid.svg --min-distance 10.0 --special-color yellow --special-color2 red --special-distance 20 --special-distance2 40 --use-localtime
```

