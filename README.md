# Instagram_Graph_API
Consommer Instagram Graph API
1°/ Consommer Instagram Graph API

- Avoir un compte Instagram professionnel(instagram id), page Facebook lié au compte Instagram (facebook id) et un token.

- Avoir les autorisations: pages_show_list , ads_management, business_management ,instagram_basic ,instagram_manage_comments ,instagram_manage_insights, instagram_content_publish, instagram_manage_messages, pages_read_engagement, pages_manage_metadata, pages_manage_posts.

- 

2°/ Récupération des publications via un hashtag

Récupérer id de hashtag.

Récupérer les publications avec les différentes propriétés (media_type,comments_count,permalink), à partir du FEED par id de hashtag.

3°/ Récupération des commentaires et l'image de publication via id de publication

- Récupération de l'image avec le lien de la réponse media_url.

- La récupération des commentaires autorisée seulement pour l'utilisateur qui a créé objet média (image, vidéo) voir le lien suivant : https://developers.facebook.com/docs/instagram-api/reference/ig-media/comments

- Création d'un web scraper pour la Récupération des commentaires via le lien de la réponse permalink.

4°/ Stockage des données

 - Stockage de la réponse de API.

 - Stockage des commentaires et image en format base64 de chaque publication avec id dans une collecstion.
