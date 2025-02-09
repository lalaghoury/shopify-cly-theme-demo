Create a Shopify theme that uses Tailwind CSS for styling and supports both light and dark modes. The theme should include a well-structured color system similar to the one below, using CSS variables inside Tailwind's @layer base. It should be modern, minimal, and highly customizable. The design should emphasize clean typography, clear spacing, and a well-balanced use of white space. Include custom color variables for primary, secondary, muted, accent, and chart colors for data visualization. The dark mode should have a rich, deep color scheme that enhances readability and contrast. Also, ensure that buttons, cards, and popovers follow the theme's color system dynamically.

Key Features:

Tailwind-based styling with @tailwind base; @tailwind components; @tailwind utilities;
Light & Dark mode support using CSS variables inside @layer base.
Shopify-compatible layout, including product grids, navigation, and checkout pages.
Customizable color system with HSL values to allow easy adjustments.
Responsive design optimized for desktop and mobile experiences.
Components for buttons, cards, popovers, and input fields following the color system.
Performance-focused to ensure fast loading times and smooth interactions.
Use the following Tailwind CSS variables for color themes:

Light Mode:

```
@layer base {
  :root {
    --background: 0 0% 100%;
    --foreground: 240 10% 3.9%;
    --primary: 142.1 76.2% 36.3%;
    --secondary: 240 4.8% 95.9%;
    --accent: 240 4.8% 95.9%;
    --muted: 240 4.8% 95.9%;
    --destructive: 0 84.2% 60.2%;
    --border: 240 5.9% 90%;
    --ring: 142.1 76.2% 36.3%;
  }
  .dark {
    --background: 20 14.3% 4.1%;
    --foreground: 0 0% 95%;
    --primary: 142.1 70.6% 45.3%;
    --secondary: 240 3.7% 15.9%;
    --accent: 12 6.5% 15.1%;
    --muted: 0 0% 15%;
    --destructive: 0 62.8% 30.6%;
    --border: 240 3.7% 15.9%;
    --ring: 142.4 71.8% 29.2%;
  }
}
```

Ensure that the theme is fully compatible with Shopify's Liquid templating engine and includes a customizable settings schema in settings_schema.json for easy branding adjustments.
