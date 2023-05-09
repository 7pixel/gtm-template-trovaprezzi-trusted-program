# Trovaprezzi Trusted Program Google Tag Manager Tag Template

Tag template ufficiale per il programma Trusted Program di Trovaprezzi.it da usare in Google Tag Manager.

![Tag Screenshot](tag-screenshot.png)



[Guida Ufficiale](https://drezzy.it/...)

## Sviluppo

- Per editare il template importare il file `template.tpl` in Google Tag Manager Template Editor e riesportarlo una volta completata la modifica
- Nel file esportato viene rimossa la riga con le categorie, questa modifica non va committata (è una stranezza, vedi guida alla pubblicazione)
- I test dove ci si aspetta un fallimento (chiamata a `gtmOnFailure`) vengono considerati falliti (altra stranezza)

### Guide

- [Guida alla pubblicazione e aggiornamento](https://developers.google.com/tag-platform/tag-manager/templates/gallery#upload_to_github)
- [Style guide](https://developers.google.com/tag-platform/tag-manager/templates/style) 

## Riferimenti

- [Tag manager custom template APIs](https://developers.google.com/tag-platform/tag-manager/templates/api)
- [Enhanced Ecommerce purchase GTM UA](https://developers.google.com/analytics/devguides/collection/ua/gtm/enhanced-ecommerce#purchases)
- [Ecommerce purchase GTM GA4](https://developers.google.com/analytics/devguides/collection/ga4/ecommerce?client_type=gtm#make_a_purchase_or_issue_a_refund)
- [Schema evento purchase GA4](https://developers.google.com/analytics/devguides/collection/ga4/reference/events#purchase)
- [Schema evento purchase UA](https://developers.google.com/analytics/devguides/collection/ua/gtm/enhanced-ecommerce#purchases)
