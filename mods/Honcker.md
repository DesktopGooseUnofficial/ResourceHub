# ✅ Honcker
A very simple mod that allows you to make your goose honk at will with the F key

## Downloads
[Honcker](https://github.com/DesktopGooseUnofficial/ResourceHub/releases/download/honcker/Honcker.dll) ![download count badge](https://img.shields.io/github/downloads/DesktopGooseUnofficial/ResourceHub/honcker/total?label=downloads&logo=github&style=plastic)
## Requirements
DesktopGoose **v0.3**

{% include install_guide.md modname="Honcker" iszip=false %}

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

