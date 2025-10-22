# TourBox Configuration Backup

This repository serves as a backup storage for TourBox presets using the TourBox Console's export/import functionality.

## Prerequisites

Make sure you have TourBox Console installed on your system.

## How to Backup TourBox Presets

### Export Presets (Backup)

1. Open TourBox Console
2. Click the export icon (first button on the right side of "Preset List")
3. Select "Export All Presets"
4. Save as `Global.tb` file in this repository
5. Commit and push the changes:
   ```bash
   git add Global.tb
   git commit -m "Update TourBox presets"
   git push
   ```

### Import Presets (Restore)

1. Open TourBox Console
2. Click the import icon
3. Select the `Global.tb` file from this repository
4. All presets will be imported and available

## Benefits

- **Single file management**: All presets in one `.tb` file
- **Version control**: Track changes to your presets over time
- **Cross-device sharing**: Easily share presets between different computers
- **TourBox native**: Uses official TourBox Console export/import functionality