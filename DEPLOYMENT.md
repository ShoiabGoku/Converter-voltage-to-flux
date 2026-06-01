# Voltage to Heat Flux Converter

This folder is ready to deploy as a small Python web app.

## Local run

```powershell
python heat_flux_app.py
```

Open:

```text
http://127.0.0.1:8765
```

## Permanent web link

To keep the app online with a permanent URL, upload these files to a Python web
hosting service such as Render, Railway, PythonAnywhere, or a VPS:

- `heat_flux_app.py`
- `heat_flux_from_voltage.py`
- `requirements.txt`
- `Procfile`

The app reads the hosting service's `PORT` environment variable automatically.
On a VPS or custom host, set:

```text
HOST=0.0.0.0
PORT=8765
```

The public URL is provided by the hosting service after deployment.
