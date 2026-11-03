
# Jira + GitHub Actions CI/CD Demo

Bu repo, Jira ile GitHub arasindaki entegrasyonu ve basit bir
CI/CD pipeline'ini gostermek icin olusturuldu.

## Amac

- Bu dosya degistirilip push edildiginde GitHub Actions tetiklenir.
- Commit ve branch adindaki Jira anahtari sayesinde sonuc Jira kartinda gorunur.

## Akis

1. Jira'da bir task acilir (ornek: `KAN-4`).
2. Task anahtarini iceren bir branch acilir: `feature/KAN-4-add-docs`.
3. Bu dosya degistirilir ve `KAN-4: docs updated` mesajiyla commit edilir.
4. GitHub Actions pipeline'i calisir ve Markdown dosyalarini kontrol eder.
5. Jira, commit, branch, PR ve build durumunu `KAN-4` kartinda gosterir.

## Degisiklik Gecmisi

- Ilk surum olusturuldu.
- KAN-4: Dokumantasyon guncellendi, CI/CD testi yapildi.
