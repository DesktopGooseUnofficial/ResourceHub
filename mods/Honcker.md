# Honcker 🙂
A very simple mod that allows you to make your goose honk at will with the F key

## Downloads
[Honcker](https://drive.google.com/file/d/1tk9ty2-m5mTgDqfmZVXrkbGiPql8NktN/view?usp=sharing)

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

---

**If your mod isn't working please look at the check list to see what  step might be missing:**

Check list:

[✓] Latest version of Desktop Goose

[✓] mod dll is in mods folder within its own folder

[✓] config file has EnableMods=True

[✓] Save the config

[✓] Restart the program