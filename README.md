# fastapps-alpic

Build with FastApps, deploy with Alpic.

## Quick Start

This is a joint project from Alpic and FastApps!

```bash
# Install dependencies
uv sync

# Start development server
uv run fastapps dev
```

This will build your widgets and start the development server.

## Creating More Widgets

```bash
uv run fastapps create another_widget
uv run fastapps dev
```

## Project Structure

```
fastapps-alpic/
├── server/
│   ├── main.py              # Server (auto-discovery)
│   └── tools/               # Widget backends
│       └── my_widget_tool.py   # Example widget
│
├── widgets/                 # Widget frontends
│   └── my_widget/
│       └── index.jsx        # Example React component
│
├── assets/                  # Built widgets (auto-generated)
├── pyproject.toml          # Python dependencies
├── uv.lock                 # Dependency lock file
└── package.json
```

## Learn More

- **FastApps Framework**: https://pypi.org/project/fastapps/
- **FastApps (React)**: https://www.npmjs.com/package/fastapps
- **uv Package Manager**: https://github.com/astral-sh/uv
- **Documentation**: https://github.com/fastapps-framework/fastapps

## License

MIT
