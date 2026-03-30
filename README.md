# Neon Storm Theme 🎨⚡

**Ultra-vivid dark theme optimized for Angular and .NET development**

Neon Storm is a vibrant, high-contrast VS Code theme designed specifically for Angular and .NET developers who want maximum color saturation and eye-catching syntax highlighting. Features electric cyan accents and neon-bright syntax colors.

![Neon Storm Theme - HTML Preview](./imagens/image-html.png)

## ✨ Features

- **🔥 Ultra-Vivid Colors** — Maximum saturation for high-impact syntax highlighting
- **⚡ Angular Optimized** — Perfect for HTML templates, TypeScript, and SCSS
- **🎯 .NET Focused** — Excellent C# support with clear attribute and type highlighting
- **💎 Neon Accents** — Electric cyan active tab borders and selection highlights
- **🌈 High Contrast** — Easy differentiation between keywords, types, functions, and variables

## 🎨 Color Palette

### Syntax Highlighting

| Token Type | Color | Hex |
|------------|-------|-----|
| **Keywords** (public, class, return, export) | ![#F7768E](https://via.placeholder.com/15/F7768E/F7768E.png) | `#F7768E` |
| **Functions/Methods** (loadEvents, CustomResponse) | ![#E0AF68](https://via.placeholder.com/15/E0AF68/E0AF68.png) | `#E0AF68` |
| **Types/Classes** (UserService, ActionResult) | ![#73DACA](https://via.placeholder.com/15/73DACA/73DACA.png) | `#73DACA` |
| **Variables/Parameters** | ![#7AA2F7](https://via.placeholder.com/15/7AA2F7/7AA2F7.png) | `#7AA2F7` |
| **Strings** | ![#9ECE6A](https://via.placeholder.com/15/9ECE6A/9ECE6A.png) | `#9ECE6A` |
| **Decorators/Attributes** (@Injectable, [Route]) | ![#BB9AF7](https://via.placeholder.com/15/BB9AF7/BB9AF7.png) | `#BB9AF7` |
| **Numbers/Constants** | ![#FF9E64](https://via.placeholder.com/15/FF9E64/FF9E64.png) | `#FF9E64` |
| **Comments** | ![#4A5F4A](https://via.placeholder.com/15/4A5F4A/4A5F4A.png) | `#4A5F4A` |

### UI Colors

| Element | Color | Hex |
|---------|-------|-----|
| **Editor Background** | ![#16161E](https://via.placeholder.com/15/16161E/16161E.png) | `#16161E` |
| **Sidebar Background** | ![#1A1B26](https://via.placeholder.com/15/1A1B26/1A1B26.png) | `#1A1B26` |
| **Terminal Background** | ![#121217](https://via.placeholder.com/15/121217/121217.png) | `#121217` |
| **Active Tab Border** | ![#00DFFF](https://via.placeholder.com/15/00DFFF/00DFFF.png) | `#00DFFF` |
| **Selection** | ![#263545](https://via.placeholder.com/15/263545/263545.png) | `#263545` |
| **Cursor** | ![#00DFFF](https://via.placeholder.com/15/00DFFF/00DFFF.png) | `#00DFFF` |

## 🚀 Installation

### From Source (Development)

1. Clone or download this repository
2. Copy the folder to your VS Code extensions directory:
   - **Windows**: `%USERPROFILE%\.vscode\extensions`
   - **macOS/Linux**: `~/.vscode/extensions`
3. Restart VS Code
4. Go to: `File` → `Preferences` → `Theme` → `Color Theme`
5. Select **Neon Storm**

### Testing the Theme

1. Open the theme folder in VS Code
2. Press `F5` to launch Extension Development Host
3. In the new window, select the theme from the Command Palette (`Ctrl+Shift+P` → "Preferences: Color Theme")

## 📁 Optimized For

This theme provides exceptional syntax highlighting for:

### Angular
- ✅ **HTML** — Tags in pink (`#F7768E`), attributes in purple (`#BB9AF7`)
- ✅ **TypeScript** — Decorators (`@Component`, `@Injectable`) in purple, types in turquoise
- ✅ **SCSS/CSS** — Selectors in turquoise, properties in blue, values in gold
- ✅ **Template Syntax** — `*ngIf`, `*ngFor`, `[routerLink]` highlighted as attributes
- ✅ **Interpolation** — `{{ }}` expressions in blue

### .NET (C#)
- ✅ **Keywords** — `public`, `class`, `using`, `return` in pink
- ✅ **Types** — `ActionResult`, `CustomResponse`, interfaces in turquoise
- ✅ **Attributes** — `[Route]`, `[HttpGet]`, `[ApiController]` in purple
- ✅ **Methods** — Function names in gold with bold styling
- ✅ **Generics** — `List<T>`, `Task<TResult>` properly highlighted

### Configuration Files
- ✅ **JSON** — Keys in turquoise, strings in green, numbers in orange
- ✅ **Markdown** — Headings in pink, links in turquoise, code blocks in blue

## 🎯 Language Support

| Language | Extension | Support Level |
|----------|-----------|---------------|
| HTML | `.html` | ⭐⭐⭐⭐⭐ |
| TypeScript | `.ts` | ⭐⭐⭐⭐⭐ |
| JavaScript | `.js` | ⭐⭐⭐⭐⭐ |
| C# | `.cs` | ⭐⭐⭐⭐⭐ |
| CSS | `.css` | ⭐⭐⭐⭐⭐ |
| SCSS/SASS | `.scss`, `.sass` | ⭐⭐⭐⭐⭐ |
| JSON | `.json` | ⭐⭐⭐⭐⭐ |
| Markdown | `.md` | ⭐⭐⭐⭐⭐ |

## 💡 Tips

- **High Contrast Mode**: Already optimized! All colors are vivid and saturated.
- **Font Recommendations**: Works great with Fira Code, JetBrains Mono, or Cascadia Code with ligatures enabled.
- **Terminal Colors**: Matches syntax highlighting for consistency (Info=Cyan, Warning=Yellow, Error=Pink).

## 🔧 Customization

If you want to tweak colors, add this to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Neon Storm]": {
      "editor.background": "#16161E",
      "tab.activeBorder": "#00DFFF"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Neon Storm]": {
      "comments": "#4A5F4A"
    }
  }
}
```

## 📸 Screenshots

### Angular TypeScript Component
![TypeScript with Neon Storm](./imagens/image-ts.png)
*TypeScript com highlighting de decorators, tipos e methods em cores neon vivas*

### C# Web API Controller
![C# with Neon Storm](./imagens/image-c.png)
*C# com attributes, keywords e types perfeitamente destacados*

### SCSS Styling
![SCSS with Neon Storm](./imagens/image-css.png)
*SCSS com selectors, properties e values em cores distintas*

### HTML Angular Template
![HTML with Neon Storm](./imagens/image-html.png)
*HTML Angular com tags, attributes e diretivas claramente diferenciadas*

## 🐛 Issues & Feedback

Found a bug or have a suggestion? Please open an issue on GitHub!

## 📝 License

MIT License - feel free to use and modify!

## 🙏 Acknowledgments

Inspired by:
- Tokyo Night Storm theme
- Neon color aesthetics
- Angular and .NET developer workflows

---

**Enjoy coding with Neon Storm!** 🚀✨⚡

Made with 💜 for Angular and .NET developers by **Bruno Cavalcante**
