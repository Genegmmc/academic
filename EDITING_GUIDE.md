# Editing Guide — Genesis Academic Site

## The only file you usually need to edit

```text
index.html
```

## 1. Change the main introduction

Find:

```html
<p class="subtitle">
  PhD research student at the University of Antwerp working on biomedical imaging,
  optical coherence tomography, and inflammation assessment for cochlear implant research.
</p>
```

Replace only the text between `<p>` and `</p>`.

## 2. Change the photo

Your photo is here:

```text
assets/profile.jpg
```

To replace it:

1. Delete the current `profile.jpg`
2. Upload your new photo
3. Rename it exactly:

```text
profile.jpg
```

## 3. Change your emails

Find:

```html
GenesisMarisol.MendozaCelorio@uantwerpen.be
genegmmc@gmail.com
```

Replace them wherever they appear.

## 4. Change LinkedIn

Find:

```html
https://www.linkedin.com/in/genesis-m-mendoza-celorio-198520178
```

Replace it with your updated LinkedIn URL if needed.

## 5. Edit the three research cards

Find:

```html
<h3>Current research</h3>
<h3>Highlights</h3>
<h3>Interests</h3>
```

Edit the paragraph below each one.

## 6. Edit Research & experience

Find:

```html
<section id="experience">
```

A timeline item looks like this:

```html
<article class="timeline-item">
  <div class="date">Present</div>
  <div>
    <div class="role">PhD Research Student</div>
    <div class="place">University of Antwerp</div>
    <p class="description">
      Your description here.
    </p>
  </div>
</article>
```

Copy and paste this block if you want to add more experience.

## 7. Remove Teaching if you do not want it

Find:

```html
<section id="teaching">
```

Delete everything from `<section id="teaching">` until its closing `</section>`.

Also remove this from the menu:

```html
<a href="#teaching">Teaching</a>
```

## 8. Add publications later

Publications are removed for now.

When you have publications, add a new section where this comment appears:

```html
<!-- Publications are intentionally removed for now.
     When you have publications, you can add a new section here. -->
```

## 9. Change colors

Find this in `index.html`:

```css
:root {
  --background: #f7f7f5;
  --card: #ffffff;
  --text: #111111;
  --muted: #5f6368;
  --line: #e5e5e0;
}
```

The main black text is controlled by:

```css
--text: #111111;
```

The background is controlled by:

```css
--background: #f7f7f5;
```

## 10. Do not delete symbols

Do not accidentally delete:

```text
< > / " = ;
```

That is the most common reason the page breaks.
