# shopping-list
Take a picture of your shopping bill and update the shopping list for the month, this can be ticked off when items are used!

Flow: 
1. Snap the picture on your phone via a PWA 
2. The image is converted to text using Google Cloud Vision API -  Detect Text (OCR)
3. 
   1. Results are sent to a Google Sheet, this adds a new sheet if it can't find the sheet with the correct date or it will add to the sheet with the date on. 
   2. Instead of using a Google Sheet the items could be stored in a database (Firebase)?  
4. An interface on the PWA will list all the items and when they are used they will be able to tick them off the list (maybe find by filter or search)
5. When ready to shop they can go onto this list and click a button to make a Google Keep shopping list.



Tools to be used: 

- Web uploads - https://cloudinary.com/features/file_upload_storage OR Firebase Cloud Storage
- Google Cloud Image recognition https://cloud.google.com/vision/docs/ocr#vision-detect-text-gcloud
- Google Sheets
- Google Keep


Testing image url: https://imgur.com/p9K3Sfg.jpg
