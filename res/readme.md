type this in CMD/terminal to make `ts` file from `ui` file:

```powershell
pylupdate5 MainWindow.ui -ts MainWindow.ts
```

open `ts` file with `linguist.exe`

then use the linguist translate all English into your language.

after translation done, select compile in linguist.

then move `ts` and `qm` file into your language folder like `ZH-CN`