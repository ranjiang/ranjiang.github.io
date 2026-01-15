# Icon Guide - How to Change Icons

Your website now uses **Lucide Icons** - a free, open-source icon library with 1000+ icons.

## Current Icons Used

- **Thoughts**: `brain` (gray)
- **Projects**: `rocket` (blue)
- **Design**: `palette` (yellow)
- **Experience**: `briefcase` (purple)

## How to Change Icons

1. **Browse Icons**: Visit [https://lucide.dev/icons/](https://lucide.dev/icons/)
2. **Search for an icon** you like (e.g., "heart", "star", "code", "music")
3. **Copy the icon name** (e.g., "heart" or "code-2")
4. **Update your HTML**: Replace the icon name in the `data-lucide` attribute

Example:
```html
<!-- Current -->
<i data-lucide="brain" class="w-7 h-7 text-gray-400"></i>

<!-- Change to heart icon -->
<i data-lucide="heart" class="w-7 h-7 text-gray-400"></i>
```

## Popular Icon Suggestions by Category

### For "Thoughts":
- `brain` (current)
- `book-open`
- `lightbulb`
- `message-square`
- `pen-tool`

### For "Projects":
- `rocket` (current)
- `code`
- `folder`
- `layers`
- `box`

### For "Design":
- `palette` (current)
- `paintbrush`
- `pen-tool`
- `brush`
- `sparkles`

### For "Experience":
- `briefcase` (current)
- `award`
- `trophy`
- `graduation-cap`
- `users`

## Change Icon Colors

You can change colors using Tailwind classes:

```html
<!-- Gray -->
<i data-lucide="brain" class="w-7 h-7 text-gray-400"></i>

<!-- Blue -->
<i data-lucide="rocket" class="w-7 h-7 text-blue-500"></i>

<!-- Yellow -->
<i data-lucide="palette" class="w-7 h-7 text-yellow-500"></i>

<!-- Purple -->
<i data-lucide="briefcase" class="w-7 h-7 text-purple-500"></i>

<!-- Red -->
<i data-lucide="heart" class="w-7 h-7 text-red-500"></i>

<!-- Green -->
<i data-lucide="leaf" class="w-7 h-7 text-green-500"></i>
```

## Change Icon Size

Adjust the `w-7 h-7` classes:
- `w-5 h-5` - Small
- `w-6 h-6` - Medium-small
- `w-7 h-7` - Medium (current)
- `w-8 h-8` - Large
- `w-10 h-10` - Extra large

## Other Free Icon Resources

If you want alternatives:

1. **Heroicons**: https://heroicons.com/ (similar style)
2. **Feather Icons**: https://feathericons.com/ (similar to Lucide)
3. **Font Awesome**: https://fontawesome.com/icons (has free tier)
4. **Simple Icons**: https://simpleicons.org/ (for brand logos)
