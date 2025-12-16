# Promps.chat Animated Logo

Animated SVG logo for [promps.chat](https://promps.chat) built with React and Framer Motion.

https://github.com/hasanharman/promps.chat-logo/raw/main/animated-logo.mp4

## 🛠️ Stack

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Motion](https://motion.dev/)

## 📦 Installation

```bash
pnpm add motion
```

## 🚀 Usage

```tsx
import { AnimatedLogo } from './animated-logo'

// Hover to animate
<AnimatedLogo size={48} />

// Or control programmatically
const logoRef = useRef<AnimatedLogoHandle>(null)
<AnimatedLogo ref={logoRef} size={48} />
logoRef.current?.startAnimation()
```

## 🙏 Inspiration

This project is inspired by [pqoqubbw/icons](https://github.com/pqoqubbw/icons) and [lucide-animated.com](https://lucide-animated.com/)

## 📄 License

MIT
