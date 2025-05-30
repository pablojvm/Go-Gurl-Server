# Go-Gurl-Server

Este repositorio es un Json-server creado para darle data a la aplicacion creada Go-Gurl

# Server Structure

## Colecciones

## Queens

{
    id,
    name,
    winner
    missCongeniality,
    isFav,
    description,
    image: [],
    seasons: []
}

## Seasons

{
    id,
    name,
    image,
    capitulos,
    queens: []
}

## Episodes

{
    id,
    title,
    numberEpisode,
    seasonId,
    episodeWinner,
    episodeLooser,
    description,
}

## Used API Endpoints in the App

- Get - En varias ocasiones para recibir la data completa o de colecciones en individual o de elementos de estas colecciones
- Post - Para crear una nueva reina
- Delete- Para borrar una reina
- Patch - Para modificar una reina con el componente de edicion o para añadirla en favoritos

# Links

- Repositorio Cliente - https://github.com/pablojvm/Go-Gurl-Client
- Repositorio Server - https://github.com/pablojvm/Go-Gurl-Server
- Deploy - go-gurl.netlify.app
- Slides - https://www.canva.com/design/DAGo6_bagJg/1kuTT2hezV4vzlZ04LPFPw/edit