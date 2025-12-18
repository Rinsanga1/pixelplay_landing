# this is colors i used for pixel play


## 1. Core Brand Colors (from the sky & machine)

### **Primary Purple ** : _Use for section backgrounds, nav bars, footers_

```css
--purple-900: #2B1646;   /* deep night sky */
--purple-800: #3B1F5C;   /* hero base */
--purple-700: #4E2A7A;   /* section backgrounds */
```


### **Secondary Lavender (UI Surfaces)** Use for cards, containers, soft dividers.

```css
--lavender-500: #7C5CC4;
--lavender-400: #9B7FE0;
--lavender-300: #C1AFE9;
```



---



## 2. Accent Colors (Glow & Interaction)

These are critical — they give life and contrast.

### **Golden Coin Accent**

Use for CTAs, highlights, icons, badges.

```css
--gold-500: #F5B642;   /* primary CTA */
--gold-400: #FFD36A;   /* hover */
--gold-300: #FFE8A3;   /* subtle glow */
```

> This ties directly to **payment + value + action**.


### **Arcade Neon Blue**

Use sparingly for active states, links, focus rings.

```css
--neon-blue-500: #4DD6FF;
--neon-blue-400: #7BE3FF;
```



---



## 3. Text Colors (Readability on Purple)

### **Primary Text (Headlines)**

```css
--text-primary: #FFFFFF;
```

### **Secondary Text (Body copy)**

```css
--text-secondary: #E6DBF5;
```

### **Muted / Meta Text**

```css
--text-muted: #B7A7D9;


```

---



## 4. Background Layers (Very Important)

Use depth like your image does.

```css
--bg-main: #3B1F5C;      /* default page background */
--bg-section: #4E2A7A;   /* feature sections */
--bg-card: #5C3A94;      /* cards */
```



---



## 5. Hero-Specific Overlay Gradient (Fixes your layout issue)

This directly solves the hero readability problem.

```css
.hero-overlay {
  background: linear-gradient(
    to right,
    rgba(59, 31, 92, 0.85),
    rgba(59, 31, 92, 0.55),
    rgba(59, 31, 92, 0.15),
    rgba(59, 31, 92, 0.0)
  );
}
```

* Text sits on **left**
* Arcade machine stays visible on **right**
* No hard split
* Keeps atmosphere intact



---



## 6. CTA Button Example

```css
.btn-primary {
  background: #F5B642;
  color: #2B1646;
  border-radius: 10px;
}

.btn-primary:hover {
  background: #FFD36A;
}
```



---



## 7. Visual Hierarchy Rule (Important)

* **Purple = environment**
* **Gold = action**
* **Blue = interaction**
* **White = clarity**




---





