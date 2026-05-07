# EN 10253-2 Multi Component Data Assistant

Open `index.html` through a local server or inside Electron. Keep the JSON files in the same folder.

Recommended local test command:

```bash
python -m http.server 8000
```

Then open: http://localhost:8000

Included datasets:
- Params_Rohrbogen_cleaned.json
- Params_Kappen_type_A_fixed.json
- Params_reducer_type_A_fixed.json
- Params_Tstueck_egal_fixed.json

The T-piece source file was corrected into `Params_Tstueck_egal_fixed.json` because the uploaded file had multiple top-level arrays and a JavaScript-style comment, which browsers cannot parse as JSON.
