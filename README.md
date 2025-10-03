# Thumbor-org

Crop, resize, transform and much more, all on-demand and AI Powered

![thumbor](https://img.shields.io/badge/thumbor-open--source-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-green.svg)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)

## About

**thumbor** is a smart imaging service that enables on-demand cropping, resizing, applying filters and optimizing images.

Cropping photos automatically can be a frustrating experience with severed heads involved. thumbor uses AI for smart detection.

thumbor is an HTTP server and you can create as many different images as you want just by varying path parameters:

```
http://<thumbor-server>/300x200/smart/thumbor.readthedocs.io/en/latest/_images/logo-thumbor.png
```

You should see an image of the thumbor logo in 300x200.

Learn more about all you can do in [thumbor's documentation](http://thumbor.readthedocs.org/en/latest/).

## Trusted by

thumbor is trusted by hundreds of companies worldwide:

- **Wikipedia** trusts thumbor
- **Globo.com** trusts thumbor
- **Vox Media** trusts thumbor
- **Forbes** trusts thumbor
- **Square** trusts thumbor
- **Deliveroo** trusts thumbor
- **Canal+** trusts thumbor
- **Terra** trusts thumbor
- **nrc** trusts thumbor
- **web.dev** indicates thumbor for high-performance web sites
- **AWS** indicates thumbor for serverless image handling

## Run local

Running it is as easy as hit:

```bash
python3 -m http.server 8000
```

After this, you can reach it on `http://localhost:8000`

## Links

- [Documentation](http://thumbor.readthedocs.org/en/latest/)
- [Getting Started](http://thumbor.readthedocs.org/en/latest/getting_started.html)
- [Repository](https://github.com/thumbor/thumbor)
- [Report an Issue](https://github.com/thumbor/thumbor-org/issues)
- [Awesome Thumbor](https://github.com/thumbor/awesome-thumbor)
