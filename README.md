# api-bblaze

## Guide d'utilisation de l'api du cabinet bblaze

curl -X GET https://api-bblaze.rembeau.com/entreprise

#### Réponse

{
  "status": "success",
  "message": "liste des entreprises et leurs emails",
  "data": [
    {
    "id": "2900",
    "name": "entreprise",
    "email": "entreprise@gmail.com"
    }
  ]
}
