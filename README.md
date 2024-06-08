[tool.poetry]
name = "my_instagram_project"
version = "0.1.0"
description = "Project configured for Instagram environment"
authors = ["Your Name <you@example.com>"]

[tool.poetry.dependencies]
python = ">=3.8.0,<3.9"
certifi = "2022.5.18.1"
charset-normalizer = { version = "2.0.12", extras = ["unicode_backport"] }
colorama = "0.4.4"
idna = "3.3"
numpy = "1.22.2"
requests = { version = "2.28.0", extras = ["socks", "use_chardet_on_py3"] }
urllib3 = { version = "1.26.9", extras = ["brotli", "secure", "socks"] }

[build-system]
requires = ["poetry-core>=1.0.0"]
build-backend = "poetry.core.masonry.api"
