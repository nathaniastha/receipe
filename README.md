# receipe
# 🍲 Culinary Planner - AngularJS SPA

## Overview
Single-page recipe management application built with **AngularJS 1.8.2** (no build tools needed).

**Features:**
- 📊 Dashboard with recipe stats & today's meal
- 📚 Recipe gallery (search, delete)
- ➕ Add new recipes (ingredients/tags)
- 📅 Weekly meal planner + auto shopping list
- 🎨 Responsive design (mobile-first)
- 💾 In-memory data (add persistence via localStorage if needed)

## 🚀 Quick Start
1. Open `receipe.html` in any modern browser
2. **No setup required** - CDN loaded

## 📱 Navigation
- **Dashboard** - Stats & today's plan
- **My Recipes** (4 preloaded + 3 added = 7 total) - Browse/delete
- **Add Recipe** - Create custom recipes
- **Weekly Planner** - Schedule meals + shopping list

## 🛒 Preloaded Recipes (7 Total)
1. Spaghetti Carbonara
2. Avocado Toast
3. Chicken Tikka Masala
4. Greek Salad
5. Margherita Pizza
6. Beef Burger
7. Chocolate Cake

## ✨ Tech Stack
```
Frontend: AngularJS 1.8.2 + Angular Route
CSS: Custom CSS variables (CSS Grid/Flexbox)
No backend/database - Pure client-side
```

## 📂 File Structure
```
receipe.html     # Main SPA (all-in-one)
styles.css       # (unused - embedded)
app.js           # (unused - embedded)
index.html       # (unused)
TODO_recipe.md   # Development log
README.md        # You're reading it!
```

## 🎯 Usage
```
1. Open receipe.html
2. Browse recipes (/recipes)
3. Add your own (/add-recipe)
4. Plan week (/planner)
5. Auto-generate shopping list!
```

## 🔧 Customization
Edit `RecipeDataService` recipes array (line ~500):
```js
{ id: 8, name: 'Your Recipe', prepTime: 30, difficulty: 'Easy', tags: ['Custom'], ingredients: ['Your ingredients'] }
```

## 📱 Responsive
✅ Mobile/Tablet/Desktop optimized
✅ Touch-friendly buttons
✅ Sticky navigation

## 🎉 Deploy
- GitHub Pages (drag receipe.html)
- Netlify/Vercel (drag-drop)
- Any static host

**Live Demo:** Open `receipe.html` now!

---

⭐ **Made with ❤️ using AngularJS**

