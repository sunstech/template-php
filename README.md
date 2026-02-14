# [Proje Adi]

[1-2 cumle aciklama]

## Gereksinimler

- PHP 8.2+
- Composer
- MySQL veya PostgreSQL

## Kurulum

```bash
git clone https://github.com/sunstech/[REPO_ADI].git
cd [REPO_ADI]
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

## Komutlar

| Komut | Aciklama |
|-------|----------|
| php artisan serve | Development server |
| php artisan test | Testleri calistir |
| php artisan migrate | Migration calistir |
| composer install | Bagimliliklari yukle |

## Git Workflow

- main - Production (sadece PR ile merge)
- develop - Development
- feature/xxx - Yeni ozellik
- fix/xxx - Bug fix

### Commit Formati
```
feat(kapsam): yeni ozellik
fix(kapsam): hata duzeltme
docs(kapsam): dokumantasyon
refactor(kapsam): kod duzenleme
test(kapsam): test ekleme
```

## Ekip

| Rol | Kisi |
|-----|------|
| Lead | [Ad] |

## Linkler

- Trello: [Board linki]
- Slack: #proje-[ad]
