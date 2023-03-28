# Capstone Project Part 2 :

- Dans cette partie on vise à stocker nos données dans Atlas Mongo DB :

![image](https://user-images.githubusercontent.com/123749462/228303995-6051c6f9-7f65-4484-8fe7-56183ebd1f46.png)

1-Modifier le code de la partie précédante et ajouter des lignes de code pour faire une connection avec Mongo DB.
## Hint :

- Aller sur votre compte Atlas MongoDB
- Aller sur Deployment > Database 
- Cliquer sur connect
![image](https://user-images.githubusercontent.com/123749462/228305553-5d5d54d1-23fb-46ff-ae8a-15d8644da37f.png)

- Cliquer sur Connect your Application :

![image](https://user-images.githubusercontent.com/123749462/228306089-a61629d1-48ce-4732-a0c5-3adb7ecb6937.png)
- Copier cette ligne :
![image](https://user-images.githubusercontent.com/123749462/228306518-95dd00e8-0d87-4058-809a-8a6630f709fd.png)


- Utiliser la méthode MongoClient avec la ligne que vous avez copier :
````
MongoClient(
  "mongodb+srv://<username>:<password>@cluster0.x2dxemb.mongodb.net/?retryWrites=true&w=majority"
)
```
