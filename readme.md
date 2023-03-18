# ManfredHu's Karabiner-Elements Configuration
Karabiner-Elements默认配置在`~/.config/karabiner/karabiner.json`下

可以查看下
```
cat ~/.config/karabiner/karabiner.json
```

# 使用

```bash
cp ./karabiner.json ~/.config/karabiner/karabiner.json
```

## Home/End 对齐Cmd + Left/Right
Home to Command Left
End to Command Right

因为HHKB有Home和End键, 这里默认对齐Cmd + Left/Right

## Right Cmd
因为Right Cmd很少用到, 自定义特别的键可以多个功能键. 但是功能键很多, 所以使用功能全组合配置, 也就是 `Right Command = Command + Option + Control + Shift`, 这么多键是个人都按不过来.

代码参考 https://ke-complex-modifications.pqrs.org/json/caps_lock.json 实现
