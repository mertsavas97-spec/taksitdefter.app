# taksitdefter.app — GitHub Pages

Statik web sitesi: App Store Connect için gerekli yasal sayfalar.

| URL | Sayfa |
|-----|-------|
| `/` | Ana sayfa |
| `/gizlilik/` | Gizlilik + KVKK |
| `/destek/` | Destek + SSS |
| `/kullanim-kosullari/` | Kullanım koşulları |

## Yerel önizleme

```bash
cd website && python3 -m http.server 8080
# http://localhost:8080
```

## Yayın (GitHub)

```bash
chmod +x scripts/publish-website.sh
gh auth login
./scripts/publish-website.sh
```

Repo: **mertsavas97-spec/taksitdefter.app** (public)

### GitHub Pages ayarı

1. Settings → Pages → Source: **main** / **root**
2. Custom domain: **taksitdefter.app**
3. Enforce HTTPS ✓

### DNS

Domain sağlayıcında apex (`taksitdefter.app`) için GitHub A kayıtları:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## App Store URL’leri

- Privacy: https://mertsavas97-spec.github.io/taksitdefter.app/gizlilik/
- Support: https://mertsavas97-spec.github.io/taksitdefter.app/destek/
- Marketing: https://mertsavas97-spec.github.io/taksitdefter.app/
