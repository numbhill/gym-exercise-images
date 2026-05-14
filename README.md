# Gym Exercise Images

This repository stores public exercise reference images used by the Notion **Gym / Exercise Library** system.

## Folder structure

```text
chest/
back/
shoulders/
legs/
arms/
abs/
```

GitHub does not keep empty folders, so each folder contains a `.gitkeep` placeholder until images are uploaded.

## Required image filenames

Use lowercase names with hyphens. Prefer `.webp` for consistency.

### Chest

```text
chest/bench-press.webp
chest/incline-bench-press.webp
chest/incline-dumbbell-press.webp
chest/flat-dumbbell-press.webp
chest/machine-chest-press.webp
chest/cable-fly.webp
```

### Back

```text
back/pull-ups.webp
back/lat-pulldown.webp
back/one-arm-cable-lat-pulldown.webp
back/chest-supported-row.webp
back/seated-cable-row.webp
```

### Shoulders

```text
shoulders/overhead-press.webp
shoulders/seated-dumbbell-shoulder-press.webp
shoulders/cable-lateral-raise.webp
shoulders/rear-delt-fly.webp
shoulders/face-pull.webp
```

### Legs

```text
legs/squat.webp
legs/romanian-deadlift.webp
legs/leg-press.webp
legs/leg-curl.webp
legs/standing-calf-raise.webp
legs/hack-squat.webp
legs/front-squat.webp
legs/bulgarian-split-squat.webp
legs/leg-extension.webp
legs/calf-raise.webp
```

### Arms

```text
arms/rope-pushdown.webp
arms/overhead-cable-triceps-extension.webp
arms/incline-dumbbell-curl.webp
arms/dumbbell-curl.webp
arms/cable-curl.webp
```

### Abs

```text
abs/cable-crunch.webp
abs/hanging-knee-raise.webp
```

## Raw URL pattern

After uploading images, each image can be used in Notion with this pattern:

```text
https://raw.githubusercontent.com/numbhill/gym-exercise-images/master/<folder>/<file-name>.webp
```

Example:

```text
https://raw.githubusercontent.com/numbhill/gym-exercise-images/master/chest/bench-press.webp
```

## Workflow

1. Download or create one clear image for each exercise.
2. Rename each file exactly as listed above.
3. Upload files into the matching folder.
4. Use the raw GitHub URLs in Notion's **Exercise Library** `Image URL` field.

## Notes

- Use images you have permission to use.
- Wikimedia Commons and open-source exercise image datasets are preferred.
- Avoid random Google Images when possible.

