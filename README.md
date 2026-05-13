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

Use lowercase names with hyphens. Prefer `.png` for consistency.

### Chest

```text
chest/bench-press.png
chest/incline-bench-press.png
chest/incline-dumbbell-press.png
chest/flat-dumbbell-press.png
chest/machine-chest-press.png
chest/cable-fly.png
```

### Back

```text
back/pull-ups.png
back/lat-pulldown.png
back/one-arm-cable-lat-pulldown.png
back/chest-supported-row.png
back/seated-cable-row.png
```

### Shoulders

```text
shoulders/overhead-press.png
shoulders/seated-dumbbell-shoulder-press.png
shoulders/cable-lateral-raise.png
shoulders/rear-delt-fly.png
shoulders/face-pull.png
```

### Legs

```text
legs/squat.png
legs/romanian-deadlift.png
legs/leg-press.png
legs/leg-curl.png
legs/standing-calf-raise.png
legs/hack-squat.png
legs/front-squat.png
legs/bulgarian-split-squat.png
legs/leg-extension.png
legs/calf-raise.png
```

### Arms

```text
arms/rope-pushdown.png
arms/overhead-cable-triceps-extension.png
arms/incline-dumbbell-curl.png
arms/dumbbell-curl.png
arms/cable-curl.png
```

### Abs

```text
abs/cable-crunch.png
abs/hanging-knee-raise.png
```

## Raw URL pattern

After uploading images, each image can be used in Notion with this pattern:

```text
https://raw.githubusercontent.com/numbhill/gym-exercise-images/master/<folder>/<file-name>.png
```

Example:

```text
https://raw.githubusercontent.com/numbhill/gym-exercise-images/master/chest/bench-press.png
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
