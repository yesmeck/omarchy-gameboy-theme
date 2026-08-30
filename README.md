# Omarchy Game Boy Theme

A nostalgic dark Omarchy theme inspired by the original handheld's olive LCD,
deep plum controls, and four-tone pixel graphics.

![Game Boy theme wallpaper](backgrounds/gameboy-landscape.png)

## Install

```bash
omarchy theme install https://github.com/YOUR_USERNAME/omarchy-gameboy-theme
```

Then select **Gameboy** from the Omarchy theme menu, or run:

```bash
omarchy theme set gameboy
```

For a local checkout that has not been pushed to Git yet:

```bash
mkdir -p ~/.config/omarchy/themes/gameboy
cp colors.toml btop.theme chromium.theme icons.theme \
  ~/.config/omarchy/themes/gameboy/
cp -r backgrounds ~/.config/omarchy/themes/gameboy/
omarchy theme set gameboy
```

## Included

- Complete Omarchy semantic and terminal palette
- Original 16:9 pixel-art wallpaper
- Hyprland olive/plum borders generated from the semantic palette
- btop, Chromium, and icon theme integrations
- Generated terminal and editor themes through Omarchy's color templates

The wallpaper is original artwork generated for this project. This is an
unofficial fan theme and is not affiliated with or endorsed by Nintendo.
