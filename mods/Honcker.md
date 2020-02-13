# 🙂 Honcker [![Honcker.dll](https://img.shields.io/badge/Click_to_download-DLL-informational?style=plastic)](https://drive.google.com/file/d/1tk9ty2-m5mTgDqfmZVXrkbGiPql8NktN/view?usp=sharing)
A very simple mod that allows you to make your goose honk at will with the F key

## Requirements
DesktopGoose **v0.3**

## Source code
```
 public class ModMain : IMod
    {

        [DllImport("user32.dll")]
        public static extern short GetAsyncKeyState(Keys vKey);
        public void Init()
        {
            InjectionPoints.PreTickEvent += PreTick;
        }        
        public void PreTick(GooseEntity goose) {
            bool pressingHonk = false;
            if (GetAsyncKeyState(Keys.F) != 0)
            {
                if (!pressingHonk)
                {
                    API.Goose.playHonckSound();
                    pressingHonk = true;
                }
            }
            else
            {
                pressingHonk = false;
            }
        }
    }
```

{% include install_guide.md modname="Honcker" iszip=false %}

