# Breakfast Suggester

A simple, offline-first app to suggest breakfast dishes and beat decision fatigue.

## Features

- **Quick Suggestions**: Tap a button to get a random breakfast suggestion
- **No Repeats**: Configurable setting to avoid suggesting the same dish within N days (0-14 days)
- **Ingredients**: Add ingredients for each dish — shown when suggested
- **Backup & Restore**: Download your dish list as JSON, restore on any device
- **Offline**: Works completely offline — all data stored locally in your browser
- **Mobile-Friendly**: Optimized for phones and tablets
- **Dark Mode**: Automatic light/dark mode based on system settings

## How to Use

### Add Dishes
1. Tap **⚙️ Manage dishes**
2. Enter dish name (e.g., "Poha")
3. Optionally add ingredients (e.g., "onions, potatoes, oil")
4. Tap **Add Dish**
5. Repeat for 5-10 favorite breakfasts

### Get a Suggestion
1. Every morning, tap **Suggest Breakfast**
2. See the dish name + ingredients
3. Cook and enjoy!

### Adjust Settings
- Tap **⚙️ Manage dishes**
- Use the slider to set "Don't repeat from last N days" (default: 3)
  - `0` = any dish allowed
  - `14` = maximum gap between repeats

### Backup & Restore
- **Backup**: Tap 📥 Backup → saves a `.json` file to your device
- **Restore**: Tap 📤 Restore → select a previously saved `.json` file → dishes restored instantly
- Use this when switching devices or phones

## Privacy & Data

- All data is stored **locally in your browser** (localStorage)
- No server, no cloud, no tracking
- Each device has its own separate data
- Backups are JSON files you control

## Technical Details

- **Stack**: Vanilla HTML, CSS, JavaScript (no frameworks)
- **Storage**: Browser localStorage
- **Hosting**: GitHub Pages (free, HTTPS included)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## Deployment

This app is deployed on GitHub Pages. To access it:
1. Visit your GitHub Pages URL: `https://yourusername.github.io/breakfast-suggester/`
2. Bookmark for easy access

To update the code:
1. Edit `index.html` directly in GitHub
2. Commit changes
3. Site updates automatically in ~30 seconds

## Future Enhancements

Potential Phase 2 features:
- Server-side storage (multi-user support)
- Suggestion history (track what was suggested when)
- Ratings (mark favorite breakfasts)
- Seasonal dish management

## License

MIT — Free to use and modify
